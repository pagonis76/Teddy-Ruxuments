# <img src="res/mipmap-xhdpi-v4/icon.png" width="50"> 2017-teddy-ruxuments
i'm currently documenting the 2017 teddy stories, but for now...
# these are the stories with the hex codes to unlock them
please use NRF connect or something similar, tap on the unknown service at the bottom (UUID:a08d...f4) then tap to "unknown characteristic" (the one with the up arrow) and click the up arrow icon, then you'll see "new value", enter the app mode hex which is listed here:
enter app mode: AA020C00F2 (this is used to actually be able to send the hex codes to unlock the stories, it makes teddy think he's connected to the app)

<img src="screenshots/step 1.jpg" width="200"> <img src="screenshots/step 2.jpg" width="200"> <img src="screenshots/step 3.jpg" width="200">

# main firmware stories:

story 1 (all about bears): AA03110001EB

story 2 (the airship): AA03110002EA

story 3 (captured by mudblubs/mudblups): AA03110003E9

story 4 (wooly and the wizard): AA03110004E8

story 5 (the missing princess): AA03110005E7

story 6 (grubby's romance): AA03110006E6

story 7 (the day teddy met grubby): AA03110007E5

story 8 (Teddy's birthday) AA03110008E4

story 9 (teddy ruxpin's Christmas): AA03110009E3

story 10 (Teddy Ruxpin lullabies): AA0311000AE2

# download-only (these are listed on the app, but there's no story bin to go along with them, you have to download them to teddy)

download to the stories are [here](https://www.mediafire.com/folder/fnvah5x8qwunw/Teddy+ruxpin+last+four+stories), or if you want all stories, they are  [here](https://drive.google.com/file/d/1tKOWU6dnWm_NVEJGMClyj4VrAovs4q7f/view)

story 11 (double grubby): AA0311000BE1

story 12 (the story of the faded fobs): AA0311000CE0

story 13 (The mushroom forest, but it has no hex, maybe it does exist somewhere but because the .bin doesn't exist anywhere i know of, it's not listed here. the hex to unlock it though may be AA0311000DDF, this is only a prediction, not anything true, it's just my guess)

story 14 (summertime): AA0311000EDE

story 15 (springtime singtime): AA0311000FDD

exit app mode: AA020D00F1 (use this to make teddy interactable again and listen to your newly unlocked stories!)

# but how to download the extra stories to Teddy?
use a cord like this: <img src="screenshots/thing.jpg" width="100">... plug it into your pc, and into teddy, a new drive will appear, then find a folder called "books" then add story11.bin, story12.bin, story14.bin and story15.bin, if you did everything correctly, there should be four new stories that don't have an intro. if they don't play, redo the hex codes for them, if they still don't play check the SOURCE:
here is the [SOURCE](https://www.reddit.com/r/teddyruxpin/comments/romz7g/story_bins/)

# proof of story13 existing and being the mushroom forest
tell me if you notice the mushroom forest anywhere on these two photos. (these are from the apk/the swf file)

<img src="images/184.jpg" width="300"> <img src="images/186.jpg" width="300">

no? well this is the mushroom forest's photo (found in the apk/swf file):

<img src="images/265.jpg" width="300">

# the app
i was looking in the apk, and i found a flash file! it's really just assets. the images inside that file are in the images folder on this repo
and appearently, the story of the faded fobs uses YeS! entertainment art

<img src="images/171.jpg" width="300">

# leftovers/oddities
there are default flash assets inside both the .obb and apk, for example there's the main character from "Doodle-Jump" <img src="images/292.png" width="50">
<img src="images/296.jpg" width="50"> <img src="images/301.png" width="50">
it's really strange, but kind of cool when you really think about it

your probably wondering why the entire repo seems.. off, it's because i accidentally ruined the original repo, so i had to reconstruct it here :(
