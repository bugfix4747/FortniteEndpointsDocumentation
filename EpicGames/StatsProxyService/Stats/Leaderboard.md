## Stats Proxy - Stat Leaderboard

URL: https://statsproxy-public-service-live.ol.epicgames.com/statsproxy/api/statsv2/leaderboards/:leaderboardName \
Method: GET \
Auth Required: Yes (`fortnite:stats READ`)

## Path Parameters

`leaderboardName`: Only known supported ones:

- `br_placetop1_keyboardmouse_m0_playlist_defaultsolo`
- `br_placetop1_keyboardmouse_m0_playlist_defaultduo`
- `br_placetop1_keyboardmouse_m0_playlist_defaultsquad`

---

_Example Response for `br_placetop1_keyboardmouse_m0_playlist_defaultsolo`_

```json
{
  "entries": [
    {
      "account": "3df0e68150f34a389781edce71f80f0a",
      "value": 7981
    },
    {
      "account": "0041d08bedc548d9a2230c4a28550594",
      "value": 7641
    }
  ],
  "maxSize": 1000
}
```
