# Fortnite Launch Arguments

This readme provides a list of launch arguments that can be used with Fortnite in the Epic Games Launcher.

## How to Use Launch Arguments

1. Open Epic Games Launcher.
2. Click your Profile on the top right corner.
3. Click settings
4. Scroll down to Fortnite
5. In the "Additional Command Line Arguments" section, enter the desired launch arguments.

## Available Launch Arguments

Below is a list of commonly used launch arguments for Fortnite:

### Rendering Options

|      Argument       |               Description               |
| :-----------------: | :-------------------------------------: |
|     `-WINDOWED`     |    Set game to run in windowed mode     |
|    `-FULLSCREEN`     |   Set game to run in fullscreen mode    |
|      `-d3d11`       |    Forces the game to use DirectX 11    |
|      `-d3d12`       |    Forces the game to use DirectX 12    |
| `-FeatureLevelES31` | Forces the game to use Performance Mode |

## Party Options

#### Set the selected gamemode when you launch Fortnite, more playlists can be found [here](https://fortnite-api.com/v1/playlists)

**Examples:**

|                  Argument                   |                    Description                    |
| :-----------------------------------------: | :-----------------------------------------------: |
|         `-IslandOverride=campaign`          |   Sets the selected playlist to Save The World    |
|   `-IslandOverride=playlist_playgroundv2`   |  Sets the selected playlist to the Creative Hub   |
|       `-IslandOverride=playlist_juno`       |    Sets the selected playlist to Lego Fortnite    |
|   `-IslandOverride=playlist_fmclubisland`   | Sets the selected playlist to Festival Jam Stage  |
| `-IslandOverride=playlist_pilgrimquickplay` | Sets the selected playlist to Festival Main Stage |
|      `-IslandOverride=0000-0000-0000`       |     Sets the selected playlist an island code     |

## Contributing

If you have any additional launch arguments that you would like to share, feel free to contribute to this readme by submitting a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
