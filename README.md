CS GO caster config
===================

# Installation
1. Go to csgo's cfg directory:  (On windows: C:\Program Files (x86)\Steam\steamapps\common\Counter-StrikeGlobal Offensive\csgo\cfg)
2. Clone the contents of the repo under folder named *caster*:
-- e.g. on cmd: `git clone https://github.com/kynarilaarnio/csgo-observer-config caster`

# Usage
- From console run `exec caster/caster`
- After above, `caster_map_<map>` (*e.g. caster_map_d2*) to load camera binds for individual map
-- Alternatively - `exec caster/pos_<map>` (*e.g. exec caster/pos_d2*)
- `caster_map_clear` to clear map specific binds (*or exec caster/pos_clear*)
- TODO feature: Run `caster_help` to get more help (*currently not implemented*)


## Binds

### Regular miscellaneous binds
- `numbers 1-0` - Switch to player number
- `Left ALT` - Follow nades
- `c` - Auto director
- `x` - Toggle X-ray
- `ctrl` - big map
- `TAB` - Scoreboard
- `F6` - Toggle console

### Camera control binds

After loading the map config, following binds should work:

##### Static overhead camera angles

- `Keypad 0` - CT base
- `Keypad ,` - T base
- `Keypad 1,4,7` - A site angles / pathways to A
- `Keypad 2,5,8` - Mid angles
- `Keypad 3,6,9` - B site angles / pathways to B

More specific camera locations can be found from file *camera_locations.txt*
or from the map specific config file comments.

##### 5 second lerps to above angles
- `Arrow down` + corresponding key from above

##### Pre defined few second lerps
- `v` - CT base
- `b` - T base
- `j` - Mid
- `n` - A site
- `m` - B site


## Todo
- Add train
- Add nuke
- Add vertigo
