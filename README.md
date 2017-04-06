# API
YoQuieroAyudar/JeVaisAider/IWantToHelp is a charity donation API

We are a non-profit association that collects donations from 2 to 10 € of users of mobile app for all the organizations (associations and foundations) that participate in the program. The donations are entirely given to the organizations for which the membership is totally free.
In England IWantToHelp, in France, association Je Vais Aider, in Spain, asociación Micro Hucha Solidaria. More countries will come.
All donations are API based defined in api.yml. We are building a service to easily make donations to world charities.

- `Swagger` is for API service definition http://editor.swagger.io/
- `POS` stands for Point Of Sale. A legal entity that promotes and support us. Country specific VAT tax applies to this entity.
- `ASSO` stands for Association. A entity that receive donations.
- `USER` stands for natural user who make donations. No VAT tax applies for this entity.

Copy/paste   api.yml in swagger to read/update last API service definition

# Legal Status
- Micro Hucha Solidaria is a legal non profit entity in Spain that can collect and redistribute donations.  https://microhuchasolidaria.org/en/api-3/
- Je Vais Aider is a legal non profit entity in France that can collect and redistribute donations. https://jevaisaider.org/fr/api-2/
- More countries will come.

# Countries
- Micro Hucha Solidaria collect and redistribute donations in Spain.
- Je Vais Aider collect and redistribute donations in France, Belgium, Swizerland,Morroco, Tunez.
- More countries will come.

# Project management
- `GIT` for Project management.
Any Golang gopher programmer can participate for backend, any Angular/React for frontend. Watch, Star this page or contact-us,  and we´ll contact you.

# API Status 0.15
API is still beta version. 
- `https://api.microhuchasolidaria.org/version` for Micro Hucha Solidaria.
- `https://api.jevaisaider.org/version` for Je Vais Aider.

# API total donation /metrics
Real time total donation endpoint made by all USERS
- `https://api.microhuchasolidaria.org/metrics` for Micro Hucha Solidaria.
- `https://api.jevaisaider.org/metrics` for Je Vais Aider.

# API technical aspects
Build on Linux Ubuntu Xenial (16.04 LTS)
- `golang`   https://github.com/golang
- `golang gin-gonic` framework for API development  https://github.com/gin-gonic/gin
- `Postgress` for database.
- `GORM` ORM library for Golang  https://github.com/jinzhu/gorm
- `Goose` for Database Migration Tool  https://bitbucket.org/liamstask/goose

# Financial API service
We use Mangopay to manage e-wallet for all entities: POS. ASSO, USERS
- `Mangopay` https://docs.mangopay.com/
- `Mangopay for Golang` Go implementation of the MangoPay HTTP REST api version 2. https://github.com/javiermanzano/mangopay2-go-sdk

# API TESTING
We use a Postman collection for service testing.




