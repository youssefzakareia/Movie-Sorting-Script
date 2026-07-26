# Movie-Sorting-Script
This script attempts to add all movies in movies directory to properly named movie folder, *(i.e The Matrix (1999) [1080p])*.
## Limitations:
  ### At this current moment it,
 - can only sort movies if they are dumped into one large movies folder, though it can include movie folders or movie videos undiscriminantly.
- cannot grab the movie date or quality if not present in some way, shape, or form in the video name.
- does not grab video source i.e BluRay, Web-rip, etc.
-  does not have the option to add more subtitle langauges on demand only arabic subs will be added to extra subs.
- does not automatically update itself.
## to get started 
in your terminal write:
```bash
sudo YOURPACKAGEMANAGER install pipx
pipx install subliminal
pipxx ensurepath
```
then 
download the scripts then navigate to the script directory on the terminal then do,
```bash 
sudo chmod +x fixshyt
sudo chmod +x cleanmovies
#Optional Step, if you want to execute as a normal command
sudo mv YOURDIRECTORY/cleanmovies /usr/local/bin/cleanmovies
sudo mv YOURDIRECTORY/fixshyt /usr/local/bin/fixshyt
```
then you're all set to use

## How to use?
Dump all your movies into one folder then,
*if optional step done*
```bash
cleanmovies
```
*if not*
```bash
#navigate to script directory on terminal then
./cleanmovies
```
then type your movie folder directory and wait
