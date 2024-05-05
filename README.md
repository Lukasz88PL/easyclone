# easyclone
This is just a bash script that aims to ease the process of cloning, moving, syncing, and other rclone operations.
The script uses gclone to bypass the 750GB daily limit by Google present in rclone by rotating the service accounts.

# Features
* Easy one-command installation from scratch does everything
* Linux, Android (Termux), & Windows (WSL/WSL2) supported
* Dynamic generation of rclone config before each operation, so no need to create any config manually
* Ability to use bookmarks for frequently used folder_ids for convenience
* Easy one-word execution to invoke the script

# How to install / update
```bash
curl -fsSkL https://bit.ly/3UvA2G0 | bash
```

Installation is as easy as just running the above command. It will set up everything from scratch. Accordingly, run it at a later stage to update the script and binaries as and when needed.
After installation, just enter ```clone``` whenever you need to execute the script henceforth.

# Prerequisites
* Generate the service accounts and have them downloaded in a folder named accounts. Follow the steps from [here](https://github.com/smartass08/Service-Accounts-to-Google-groups/blob/master/README.md) if you don't have service accounts yet.
* Create a new repository named accounts in your GitHub account and upload all the service account JSON files directly in that repo.

# Credits
* [rclone](https://github.com/rclone/rclone)
* [gclone](https://github.com/donwa/gclone)
* [l3v11](https://github.com/l3v11)
