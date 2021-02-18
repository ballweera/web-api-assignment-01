# WEB-API Assignment-01

### Create RESTful API below
- GET /weather?callLetters=[value]

The sample response is below
```json
[
  {
    "position": { "type": "Point", "coordinates": [-59.5, 44] },
    "callLetters": "RIGG",
    "airTemperature": { "value": -4.4, "quality": "1" },
    "ts": 1984-03-05T15:00:00.000+00:00
  },
  {
    "position": { "type": "Point", "coordinates": [-59.5, 44] },
    "callLetters": "RIGG",
    "airTemperature": { "value": -4.4, "quality": "1" },
    "ts": 1984-03-05T15:00:00.000+00:00
  }
]
```

## Instructions
- Connect to data on Mongo Atlas
- Use database `sample_weatherdata`
- Use data from collection `data`

## Condition
- Must commit source code to github account
- Required at least 2 commits: initiate project and include installed required packages, and finish GET /weather?callLetters=<value>
- node_modules/ must be excluded from git repo
- The program must be able to run on local machine
