# EV_Chargers

Where to install new Electric Vehicles Station Chargers in the Metropolitan Region of Chile?

There are currently 161 charging points for electric vehicles in Santiago de Chile (RM) and a total of 443 chargers (source: Ministry of Energy). Possible locations where to install a new charging station can be sectors near shopping centers, restaurants, cinemas, banks, parking lots, hospitals, etc. Places where users park their vehicles for a reasonable amount of time to charge them.

All those points of interest (POIs) were identified using the OpenStreet Map OSMnx library. Then, the distance between each of these POIs and the existing charging stations was calculated, and those that would have less than one charging station within a 3km radius were chosen. The chosen POIs are classified into clusters where the installation of new charging stations could be recommended.
