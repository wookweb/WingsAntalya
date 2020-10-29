### Wings Rent a Car API Documentations

ENDPOINT: https://api.wingsantalyarentacar.com/


**Open Endpoints**

| URL | Method | Params | Auth required | Description | Success Response |
| :---------------------:|:--------:|:-------:|:-------:  | :-------: | :-------: |
| /locations | GET | - | NO | Sistemdeki illerin ve lokasyonların listesi | `status` `data` `message` |
| /car-list | POST | 'date_start' 'date_end' | NO | Araçların fiyatları ve bilgileri | `status` `data` `message` |
