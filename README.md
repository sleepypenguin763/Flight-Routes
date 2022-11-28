## What is this
This make a virtual REST API server on GitHub repository.
By analyzing JSON files, the script makes directories and some files.
User can access datas of JSON file as if REST API server


## Directory Setup
```
main
├── routes
│   ├── Folder name: First 3 character of ICAO airline code
|        ├── Folder name: Full flight callsign (i.e.: UAL1)
|               ├── Callsign ── index.html
|               ├── Code ── index.html
|               ├── Number ── index.html
|               ├── AirlineCode ── index.html
|               ├── AirportCodes ── index.html
|        ├── index.html
│   ├── index.html

```

|  data you want  |  REST API URL  |
| ---- | ---- |
|  All Routes of Given Airline[Airline=ANA]   |  https://sleepypenguin763.github.io/Flight-Routes/routes/ANA/  |
|  Routes of Given Callsign[Airline=ANA1]   |  https://sleepypenguin763.github.io/Flight-Routes/routes/ANA/ANA1  |
