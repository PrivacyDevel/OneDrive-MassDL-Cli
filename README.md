# OneDrive MassDL-Cli
OneDrive MassDL-Cli allows you to easily download public OneDrive folders from your Terminal with one simple command! \
It is also capable of resuming aborted downloads and it will only download files that have been newly added or changed remotely when you re-run it with the same URL again.

## Installation
1. Install python3
2. Download the file `down`

## Usage
To download a folder from OneDrive just execute the following command: \
`./down 'https://onedrive.live.com/?authkey=XXXXX&id=XXXXX&cid=XXXXX'` \
If the download gets interrupted for any reason or you want to download the files that have been updated since your last download, just run the same command again. \
Only files that have been newly added or changed remotely are going to be download. Files that haven't changed will be skipped. \
If you want to forcefully re-download those files, you need to delete the `data.db` file and run the command again.
