# SMP Endpoint
Read on /v2/smp here.

### Base endpoint
/v2/smp does not return anything at the moment, although we are planning to make this return the endpoints it has inside of it.

## /v2/smp/econ
This endpoint will return ECONOMY player data.

For example, api.plaguecraft.xyz/v2/smp/econ would return:
```json
{
  "status": "200 OK",
  "error": null,
  "response": [
    {
      "uuid": "06abc951-435a-42f0-98e6-67c2ac4a97d7",
      "balance": 200
    },
```
### Parameters
* player - Returns a specific players data

### Command Line Example
```bash
curl "https://api.plaguecraft.xyz/v2/smp/econ" -X GET
```

## /v2/smp/skills
This endpoint will return SMP SKILLS player data.

For example, api.plaguecraft.xyz/v2/smp/skills would return:
```json
{
  "status": "200 OK",
  "error": null,
  "response": [
    {
      "ID": "uuid",
      "NAME": "name",
      "AGILITY_LEVEL": 0,
      "AGILITY_XP": 0,
      "ALCHEMY_LEVEL": 0,
      "ALCHEMY_XP": 0,
      "ARCHERY_LEVEL": 0,
      "ARCHERY_XP": 0,
      "DEFENSE_LEVEL": 0,
      "DEFENSE_XP": 0,
      "ENCHANTING_LEVEL": 0,
      "ENCHANTING_XP": 0,
      "ENDURANCE_LEVEL": 0,
      "ENDURANCE_XP": 0,
      "EXCAVATION_LEVEL": 0,
      "EXCAVATION_XP": 0,
      "FARMING_LEVEL": 0,
      "FARMING_XP": 0,
      "FIGHTING_LEVEL": 0,
      "FIGHTING_XP": 0,
      "FISHING_LEVEL": 0,
      "FISHING_XP": 0,
      "FORAGING_LEVEL": 0,
      "FORAGING_XP": 0,
      "FORGING_LEVEL": 0,
      "FORGING_XP": 0,
      "HEALING_LEVEL": 0,
      "HEALING_XP": 0,
      "MINING_LEVEL": 0,
      "MINING_XP": 0,
      "SORCERY_LEVEL": 0,
      "SORCERY_XP": 0
    }
  ]
}
```

### Parameters
* player - Returns a specific players data

### Command Line Example
```bash
curl "https://api.plaguecraft.xyz/v2/smp/skills" -X GET
```