# duplicati
Store securely encrypted backups on cloud storage services. Duplicati is a free, open source, backup client that securely stores encrypted, incremental, compressed backups on cloud storage services and remote file servers. It works with:     Amazon S3, OneDrive, Google Drive, Rackspace Cloud Files, HubiC, Backblaze (B2), Amazon Cloud Drive (AmzCD), Swift / OpenStack, WebDAV, SSH (SFTP), FTP, and more!

Homepage: https://www.duplicati.com/

### Install:
```
kcp -i gtk-sharp-2
kcp -i duplicati
```

### Management:
UI can be accessed via following URL: http://localhost:8200

Running duplicati user instance (using current user account)
  - to reload user systemd modules:        systemctl --user daemon-reload
  - to start duplicati manually:           systemctl --user start duplicati
  - to autostart duplicati on user login:  systemctl --user enable duplicati
