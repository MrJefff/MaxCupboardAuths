This plugin allows player to only authorise to a certain amount of tool cupboards.

## Permissions
- `maxcupboardauths.exempt` -- players with this permission are exempt from the maximum allowed limit and can auth to as many cupboards as they want to.

## Notes
- **It is highly recommend that you wipe the datafile after every wipe.**

## Configuration File
```json
{
  "Settings": {
    "Max Auths Allowed Per Cupboard": 5,
    "Max Auths Allowed Per Player": 5,
    "Monitor Auths Per Cupboard": false,
    "Monitor Auths Per Player": true
  }
}
```
- **Monitor Auths Per Cupboard** - turning this on will restrict how many cupboards each player can auth to
- **Monitor Auths Per Cupboard** - turning this on will restrict how many people can auth to each cupboard.

**Please note, you can use both of these at the same time**
