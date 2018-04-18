This project includes two table "vehicle" and "driver". The database is exported as
CSV format for your reference. 
Table content- "driver"
columns - name, v_number , contact - here v_number and contact are primary keys.

Table content- "vehicle"
columns - number,distance_covered,start_time,last_updated,last_stop, status, latitude and 
longitude.

here number acts as a primary key and also as foreign key which refrences the v_number attribute 
in driver table.


Google Maps-

Depending on the status of the vehicle they are indicated with
red - stopped
green - running
yellow - scheduled
blue - status not known.
Assumption made- Latitude and Longitude values are updated by the GPS device in the vehicle and updated to database.

By using this values we locate them on the google maps.

Images of the project  have been attached for a fewer values in the database.