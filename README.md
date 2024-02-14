# ZTNA_APP_TESTING
This repo allows you to employ a docker compose file with a set of apps for ZTNA testing.

Before pulling and running docker compose up. The following prerequisites should be in place.

1. Have Docker Engine and Docker Composed installed
2. Create the following directory structure:
   * myapps, then subfolders: data1, data2, data3
3. Create a .env file under myapps folder and add the following entries:
   * APPUSER="value"
   * SECRET="value"
4. Pull repo and move docker-compose.yaml file to myapps folder
5. Issue docker compose up inside myapps folder
