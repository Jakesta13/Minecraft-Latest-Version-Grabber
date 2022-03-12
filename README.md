# Minecraft-Latest-Version-Grabber
Just some PHP to download the latest server version of minecraft, one shows the sha1 that is also provided by mojang.

## Function
* [version.php](https://jakesta13.github.io/Minecraft-Latest-Version-Grabber/version.php) will output the sha1, useful for other scripts to version check.
* [latest.php](https://jakesta13.github.io/Minecraft-Latest-Version-Grabber/latest.php) will output the link to download the latest server jar.

Unfortunately PHP cannot be hosted as a Git Repo Page.  
To run these scripts to get the desired outcome, execute using `php (script).php`

## Usage with sha1sum
You need to format a .sha1 file as so: "(sha1 hash) filename.file"  
To do this in one line use `echo "$(php version.php) server.jar" > sha1-filename.sha1`  
Otherwise sha1sum command will not let you check the hash using `sha1sum (sha1-filename.sha1)`