# PVP Endpoint
Read more about the PVP endpoint here.

### /v2/pvp
v2/pvp does not return anything at the moment, although we are planning to make this return the endpoints it has inside of it.

### /v2/pvp/sw
This endpoint returns all SKYWARS data.

For example, api.plaguecraft.xyz/v2/pvp/sw, returns:
```json
{
  "status": "200 OK",
  "error": null,
  "response": [
    {
      "player_id": 1,
      "uuid": "uuid",
      "player_name": "name",
      "wins": 0,
      "losses": 0,
      "kills": 0,
      "deaths": 0,
      "xp": 0
    }
  ]
}
```

### Parameters
* player - Returns data from a specific player

### Command Line Example
```bash
curl "https://api.plaguecraft.xyz/v2/pvp/sw" -X GET
```