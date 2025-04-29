haxelib install lime
haxelib install openfl    
haxelib install flixel 4.11.0
haxelib set flixel 4.11.0
haxelib run lime setup
haxelib install flixel-tools
haxelib run flixel-tools setup
haxelib install flixel-ui
haxelib install hscripthaxelib
install newgrounds 1.1.5
haxelib set newgrounds 1.1.5
haxelib git polymod https://github.com/larsiusprime/polymod.git
haxelib git discord_rpc https://github.com/Aidan63/linc_discord-rpc
git clone https://github.com/FunkinCrew/Funkin.git
haxelib git flixel-addons https://github.com/HaxeFlixel/flixel-addons
cd Funkin
lime test html5 -debug
lime build html5 -release -clean
