### Wings Rent a Car API Documentations

ENDPOINT: https://api.wingsantalyarentacar.com/


**Open Endpoints**

| URL | Method | Params | Auth required | Description | Success Response |
| :---------------------:|:--------:|:-------:|:-------:  | :-------: | :-------: |
| /locations | GET | - | NO | Sistemdeki illerin ve lokasyonların listesi | `status` `data` `message` |
| /car-list | POST | `date_start` (Y-m-d H:i:s) `date_end` (Y-m-d H:i:s) | NO | Araçların fiyatları ve bilgileri | `status` `data` `message` |
