# API
YoQuieroAyudar/JeVaisAider/IWantToHelp API


We are a non-profit association that collects donations from 2 to 10 € of users of mobile app for all the organizations (associations and foundations) that participate in the program. The donations are entirely given to the organizations for which the membership is totally free.
In England IWantToHelp, in France, association Je Vais Aider, in Spain, asociación Micro Hucha Solidaria. More countries will come.
All donations are API based. We are building a service to make donations to charities.

- `Swagger` is for API service definition http://editor.swagger.io/
- `POS` stands for Point of sale. A legal entity that promotes and support us.
- `ASSO` stands for Association. A entity that receive donations.
- `USER` stands for natural user who make donations.

Copy/paste   api.yml in swagger to read/update last API service definition

# API Status
Check
- `https://api.microhuchasolidaria.org/version` for Micro Hucha Solidaria
- `https://api.jevaisaider.org/version` for Je Vais Aider

# API total donation /metrics
Real time total donation endpoint made by all USERS
- `https://api.microhuchasolidaria.org/metrics` for Micro Hucha Solidaria
- `https://api.jevaisaider.org/metrics` for Je Vais Aider

# API technical aspects
On Linux Ubuntu
- `golang`   https://github.com/golang
- `golang gin-gonic` framework for API development  https://github.com/gin-gonic/gin
- `Postgress` for database
- `GORM` ORM library for Golang  https://github.com/jinzhu/gorm
- `Goose` for Database Migration Tool  https://bitbucket.org/liamstask/goose
- `GIT` for Project management

# Financial API service
We use Mangopay to manage e-wallet for all entities: POS. ASSO, USERS
- `Mangopay` https://docs.mangopay.com/
- `Mangopay for Golang` https://github.com/javiermanzano/mangopay2-go-sdk


# API TESTING
We use a Postman collection



