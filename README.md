# radarr-sonarr-watchmon

#### This is a forked repo!

This script checks for recently watched movies/episodes on Trakt and changes the profile in Radarr (Sonarr not supported ATM).

Use case: downgrade the movie when watched to save some disk space

Copy config.example.yml to config.yml and change settings.

If you do not want to use either Sonarr or Radarr just comment out those settings.

First run should be done interactively to get authorized to Trakt.
The authorization is then saved to a file and the script can be run periodically in e.g. crontab.

TODO:

- [ ] Create blacklist for awesome movies which aren't allowed to downgrade
