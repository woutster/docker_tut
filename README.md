### Run the application
Just run `docker-compose up` from the root folder to run the two dashboards.
Or run `docker-compose up -d` when you don't want to see the excess logs.


### Configuration
Port for barplot dashboard is 8050.
Port for histogram dashboard is 8051.
If for any reasone these ports needs to be changed make sure to update both `application.py` port and the `docker-compose.yml` exposing for a working version again.