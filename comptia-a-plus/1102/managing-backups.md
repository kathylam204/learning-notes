# Managing Backups
## Differential Backup
- subsequent backups contain data changed since the last full backup
## Incremental Backup
- subsequent backups contain data changed since the last full backup and the last incremental backup
- a restoration requires the last full backup and all of the incremental backups
## Synthetic Backup
- the first full backup copies every file
- subsequent full backups are created from previous backups
## On Site Backups
- no internet link required
- data is immediately available
- generally cheaper than off site backups
## Off Site Backups
- requires a WAN or internet link
- data is available after a disaster
- restoration can be performed from anywhere
## Grandfather-Father-Son (acronym)
- GFS
## Grandfather-Father-Son
- three separate backup rotations
- monthly, weekly, and daily
## 3-2-1 Backup Rule
- 3 copies of data should always be available
- 2 different types of media should be used
- 1 copy of the backup should be off site
