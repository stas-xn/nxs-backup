# Changelog
All notable changes to this project will be documented in this file.

## [Unreleased]

## [2.1.1] - 2018-10-18
### Fixes
- Fixed database jobs processing
- Removed packages installation from code

## [2.1.0] - 2018-10-17
### Adds
- Ability to upload backup on custom S3 server
- Ability to use external SMTP servers
- Handling unexpected exceptions

### Changes
- Improved algorihtm for create incremental files backups
- Improved control for duplicated nxs-backup processes
- Disabled log messages bufferization
- Renamed type `mysql_xtradb` to `mysql_xtrabackup`

### Fixes
- Rpm packages build
- Unexpected program termination due to umount error
- Prelink breaks nxs-backup binary
- Closing log-file after nxs-backup termination
