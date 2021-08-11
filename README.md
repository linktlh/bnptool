## Simple Commandline interface for creating BNPs via BCML

### Setup

Install a compatible version of python for [BCML](https://github.com/NiceneNerd/BCML/) then run `pip install bnptool`

### Create a BNP 

	bnptool create Path/To/Mod
	
### Full Usage:

	bnptool create [-h] [--output OUTPUT] [--name NAME] [--version VERSION] [--description DESCRIPTION]
            [--image IMAGE] [--url URL] [--lowestpriority] [--disablepacks] [--disableaamp]
            [--disabledrops] [--disabletext] [--disableactorinfo] [--disableshrineent] [--disablemaps]
            [--disablegamedata] [--disablesavedata] [--disableeventinfo] [--disablestatuseff]
            [--disableresactors] [--disablequests] [--disablerstb] [--norstbest] [--mergetextalllang]
            Path/To/Mod

### Example Usage:
```ps
bnptool create --name "Linkle Mod - Dialogue Fix" -i "https://images.gamebanana.com/img/ss/mods/530-90_605f95e938639.jpg" -u "https://gamebanana.com/mods/33334" -d "Linkle Mod - Dialogue Fix git-28224c4b" --version "1.5.1" --mergetextalllang C:\Users\linktlh\Desktop\Ballad\wiiu\GP
```

