### URL
`https://s3.cn-north-1.amazonaws.com.cn/twa-game-data.arena.neshgameservers.com/rules/delta/triggers/stable.{ID}.json`

### Method
`GET`

### Sample request
`https://s3-eu-west-1.amazonaws.com/twa-game-data.twaservers.com/rules/arena-main/triggers/stable.json.301B9495C57E4A3A44267BFD6480D5B1`

### Sample response

```json
[
  {
    "valid_from": 1426764240,
    "valid_to": 32515643520,
    "trigger": "party_member",
    "effects": [
      {
        "bonus": "unit_xp_cents",
        "value": 0.1,
        "type": "preadd_percentage"
      }
    ]
  },
  {
    "valid_from": 1426764240,
    "valid_to": 32515643520,
    "trigger": "premium_one_minute",
    "effects": [
      {
        "bonus": "free_xp_cents",
        "value": 0.5,
        "type": "preadd_percentage"
      },
      {
        "bonus": "unit_xp_cents",
        "value": 0.5,
        "type": "preadd_percentage"
      },
      {
        "bonus": "silver_cents",
        "value": 0.5,
        "type": "preadd_percentage"
      }
    ]
  },
  {
    "valid_from": 1426764240,
    "valid_to": 32515643520,
    "trigger": "premium_unit",
    "effects": [
      {
        "bonus": "free_xp_cents",
        "value": 0.5,
        "type": "preadd_percentage"
      },
      {
        "bonus": "unit_xp_cents",
        "value": 0.5,
        "type": "preadd_percentage"
      },
      {
        "bonus": "silver_cents",
        "value": 0.5,
        "type": "preadd_percentage"
      }
    ]
  },
  {
    "valid_from": 1535373120,
    "valid_to": 1924952460,
    "trigger": "single_use_activity_trigger",
    "effects": [
      {
        "bonus": "item",
        "value": "630099746992321623",
        "type": "add"
      }
    ]
  },
  {
    "valid_from": 1575634440,
    "valid_to": 1924952460,
    "trigger": "single_use_activity_trigger",
    "effects": [
      {
        "bonus": "silver_cents",
        "value": 300000,
        "type": "add"
      }
    ]
  }
]
```
