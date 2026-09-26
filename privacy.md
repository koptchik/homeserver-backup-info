---
layout: default
title: Privacy Policy — HomeServer Backup
---

# Privacy Policy

Last updated: September 27, 2026.

## Purpose

HomeServer Backup is a personal application that uses restic and
rclone to store its owner's encrypted backups in Google Drive.

## Google account access

The application uses OAuth authorization and the drive.file scope
to access files created by, or explicitly authorized for, the
application. It uses this access to upload, read, restore, and
manage backup files.

OAuth tokens are stored on the owner's backup server and used
to maintain authorized access to Google Drive.

## Backup data

Backup contents are encrypted locally by restic before being
uploaded. Google Drive stores the encrypted backup repository.
The restic repository password is managed separately by the owner.

Data is not sold or used for advertising. Backup data is sent to
Google Drive to provide the requested storage functionality.

## Retention and control

The owner controls backup retention and can delete backups using
restic or delete the repository from Google Drive.

Google account access can be revoked through the Google Account
permissions settings. Revoking access does not delete previously
uploaded backups.

## Contact

For questions, contact the maintainer through
[GitHub Issues](https://github.com/koptchik/homeserver-backup-info/issues).

Please do not include passwords, OAuth tokens, or backup contents
in public issues.
