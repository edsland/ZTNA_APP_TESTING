# ZTNA_APP_TESTING
This repo allows you to employ a docker compose file with a set of apps for ZTNA testing.

Before pulling and running docker compose up. The following prerequisites should be in place.

1. Have Docker Engine and Docker Composed installed
2. Update ```sudo nano ~/.bashrc``` with environment variables($APPUSER and $SECRET)
   * export APPUSER=value
   * expory SECRET=value
   * Restart shell with ```source ~/.bash_profile```
4. Create the following directory structure:
   * myapps, then subfolders: data1, data2, data3
5. Pull repo and move docker-compose.yaml file to myapps folder
6. Issue docker compose up inside myapps folder
