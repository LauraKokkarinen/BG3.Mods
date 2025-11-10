These mods are provided as is. I do not promise to actively support them or fix them if any issues are discovered. Feel free to fork the repo, fix any possible issues yourself, and submit a pull request.

# Contributing

If you wish to edit the mods, you can use the Baldur's Gate 3 Toolkit to do so. If you have installed Baldur's Gate 3 via Steam, you can find the toolkit in your Steam library under Tools. YouTube has plenty of modding tutorials to get you started.

To effortlessly synchronize the local mod files with the GitHub repository, create symbolic links between the repo directories and the four local modding directories. You can do that by running the following commands (after updating them with your local paths) from the command line with admin privileges. You need to do this individually for each mod you wish to edit.

`mklink /d "C:\Program Files (x86)\Steam\steamapps\common\Baldurs Gate 3\Data\Editor\Mods\KethericsGloves_8517830f-a9e1-be14-de59-b3ef4302015c" "C:\_github\LauraKokkarinen\BG3.Mods\Editor\Mods\KethericsGloves_8517830f-a9e1-be14-de59-b3ef4302015c"`

`mklink /d "C:\Program Files (x86)\Steam\steamapps\common\Baldurs Gate 3\Data\Mods\KethericsGloves_8517830f-a9e1-be14-de59-b3ef4302015c" "C:\_github\LauraKokkarinen\BG3.Mods\Mods\KethericsGloves_8517830f-a9e1-be14-de59-b3ef4302015c"`

`mklink /d "C:\Program Files (x86)\Steam\steamapps\common\Baldurs Gate 3\Data\Projects\KethericsGloves_8517830f-a9e1-be14-de59-b3ef4302015c" "C:\_github\LauraKokkarinen\BG3.Mods\Projects\KethericsGloves_8517830f-a9e1-be14-de59-b3ef4302015c"`

`mklink /d "C:\Program Files (x86)\Steam\steamapps\common\Baldurs Gate 3\Data\Public\KethericsGloves_8517830f-a9e1-be14-de59-b3ef4302015c" "C:\_github\LauraKokkarinen\BG3.Mods\Public\KethericsGloves_8517830f-a9e1-be14-de59-b3ef4302015c"`