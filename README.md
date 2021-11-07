# shellScriptingProject
TASK: You have a folder full of unsorted files. The file
types have many different names and extensions.

Your job is to copy every file from the unsorted
folder and place it into the correct sorted sub folder.

Some files will need to appear in multiple sub
folders. Other files don't belong in any folder - they
should be removed.

The final directory structure should be as follows:
~/irimina$ (yours will reflect your account)
   - unsorted
   - sorted
        - gifs (contains all the .gif files)
        - jpgs (contains all the .jpg files)
        - txts
            - home(contains all the .txt files with the word 'home' in the title)

            - business (contains all the .txt files with the word 'business' in the title)

            - other(contains all the .txt files with neither 'word' nor 'home' in the title)

            - zero(contains all the files where the last character is the number 0 [ ...0.jpg] )

            - five (contains all the files where the last character is the number 5 [ ...5.gif] )

            - favorites (contains at least 5 of your favorite images, prefixed with the word "fav_" )


Resources:
https://linuxcommand.org/lc3_lts0050.php
