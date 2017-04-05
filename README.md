# API
YoQuieroAyudar/JeVaisAider/IWantToHelp API


We are a non-profit association that collects donations from 2 to 10 € of users of mobile app for all the organizations (associations and foundations) that participate in the program. The donations are entirely given to the organizations for which the membership is totally free.
In England IWantToHelp, in France, association Je Vais Aider, in Spain, asociación Micro Hucha Solidaria. More countries will come.

- `Swagger` for API service definition http://editor.swagger.io/
- `POS` stands for Point of sale. A legal entity that promotes and support us.
- `ASSO` stands for Association. A entity that receive donations.
- `USER` stands for natural user who make donations.

Copy/paste   api.yml in swagger to read/update last API service definition

# API Status
Check
- `https://api.microhuchasolidaria.org/version` for Micro Hucha Solidaria
- `https://api.jevaisaider.org/version` for Je Vais Aider

# API total donation /metrics
Total donation made by USER
- `https://api.microhuchasolidaria.org/metrics` for Micro Hucha Solidaria
- `https://api.jevaisaider.org/metrics` for Je Vais Aider

# API technical aspects
We use on Linux Ubuntu
- `golang` 
- `golang gin-gonic` for API development
- `Postgress` for database
- `GORM` for ORM
- `Goose` for Database Migration Tool




