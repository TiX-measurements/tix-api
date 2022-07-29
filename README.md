First Run:

1) Create mysql database
2) Set credentials in db.js file (will change it into a json file in the future
3) To run locally, run node server.js
3.1) To run on server, run pm2 server.js


You will need to have an IpToAs instance created (since the function will fetch the data from there).
1) Clone https://github.com/mannias/IpToAs/tree/master/sources
2) Create Database in mysql
3) Set credentials in the configuration file
4) Download the files: python download_files.py
5) Run the aggregator script: python principal.py

If you have some problems downloading files, just download them manually.

When the server is initialized for the first time, it will create an admin user. Set the environment variables `TIX_API_USER` and `TIX_API_PASSWORD` to define the credentials.
