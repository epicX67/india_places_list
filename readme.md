# India all place list with pincode

### raw.json

Raw file contains all the place details in a array which is described below

```json
[
  {
    "state": "Delhi",
    "district": "Central delhi",
    "place": "New Delhi",
    "pin": 110001
  }
]
```

### nest.json

Nest file contains all place name and pincode in a nested format which is described below

```json
[
  {
    "type": "state",
    "value": "Delhi",
    "districts": [
      {
        "type": "district",
        "value": "Central delhi",
        "places": [
          {
            "type": "place",
            "pin": 110001,
            "value": "New Delhi"
          }
        ]
      }
    ]
  }
]
```
