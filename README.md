# TimeWeatherChanger

Change the weather and time with GUI-based mod

## Controls

In order to open panel, press keypad "Home" by default or open game console with tilde(~) and write "twc"

You can change the key in the game menu, to open it, press F12 on your keyboard and expand SamSWAT.TimeWeatherChanger section. Press on the `Time Weather Panel Toggle Key` option and choose the key you like. If you launched the game with this mod at least once, you can find `com.samswat.timeweatherchanger.cfg` file in the `BepInEx/config/` and change keybind here too.

## How to install

1. Download the latest release here: [link](https://dev.sp-tarkov.com/SamSWAT/TimeWeatherChanger/releases) -OR- build from source (instructions below)
2. Extract the zip file `SamSWAT.TimeWeatherChanger` into your root SPT-AKI directory near `EscapeFromTarkov.exe`.
3. Inside `BepInEx/plugins` folder you should see `SamSWAT.TimeWeatherChanger.dll`

## Preview

![preview](https://media.discordapp.net/attachments/891823733499629619/928128516720062495/unknown.png)

## How to build from source

1. Download/clone this repository
2. VS2019 > File > Open solution > `SamSWAT.TimeWeatherChanger.sln`
3. VS2019 > Build > Rebuild solution
4. `SamSWAT.TimeWeatherChanger.dll` should appear in `bin\Debug` directory
5. Copy the .dll into the `BepInEx/plugins` folder
6. That's it, you have a working release of this mod.