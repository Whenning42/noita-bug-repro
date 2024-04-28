The April 8th Noita build won't launch this minimal repro mod when both
`request_no_api_restrictions="1"` and `is_game_mode="1"` in mod.xml.
The older February build on Steam however does support using both these settings
together.

Steps to reproduce:

Install this mod and optionally delete the either of the problematic mod.xml
settings. If this mod loads successfully, on a new game, the player will start
in the mines. If the mod doesn't load, then on a new game, the player starts
in the usual spot.
