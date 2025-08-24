# ResoniteVarjoEyeTracking 

A [ResoniteModLoader](https://github.com/resonite-modding-group/ResoniteModLoader) mod for [Resonite](https://resonite.com/)  
Integrates Varjo's eye tracking into Resonite. Tracks per eye and combined:
- Eye Openness
- Gaze Origin
- Gaze Direction
- Pupil Diameter
- Focus Distance
- Timestamp

Related issue on the Resonite Github:
https://github.com/Resonite-Metaverse/ResonitePublic/issues/3226

## Usage
1. Install [ResoniteModLoader](https://github.com/resonite-modding-group/ResoniteModLoader).
2. Download [VarjoEyeIntegration.dll](https://github.com/Wolf-Seisenbacher/ResoniteVarjoEyeTracking/releases/download/v2.0.1/VarjoEyeIntegration.dll) and place in your rml_mods folder
3. Download [VarjoLib.dll](https://github.com/Wolf-Seisenbacher/ResoniteVarjoEyeTracking/releases/download/v2.0.1/VarjoLib.dll) and place in your rml_libs folder
4. Start the game!

If you want to verify that the mod is working you can check your Resonite logs, equip an eye-tracking ready avatar, or create an EmptyObject with an AvatarRawEyeData Component (Found under Users -> Common Avatar System -> Face -> AvatarRawEyeData).

### Credits

To everyone who helped me test this, thank you so much! And thanks to [m3gagluk](https://github.com/m3gagluk)'s for their [VarjoCompanion](https://github.com/m3gagluk/VarjoCompanion) and [Geenz](https://github.com/Geenz) for the SDK 3.5 refactor.

Original mod created by DfgHiatus!
