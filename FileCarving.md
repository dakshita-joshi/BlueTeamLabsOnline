In this challenge, a dd file was given, and we had to recover the files that were lost. The tools that were used were Photorec, Scalpel, and Testdisk.

I used Photorec to recover files from the dd file. Flag 1 was WELOVEBTLO that was clear as day on one of the files.

Flag 2 was on the Word Document. I Base64'ed it and got the Flag. It was ASOLIDDEFENDER.

The PDF said now find Flag 3 so i put it in metadata2go and the author tag gave Flag 3. It had percentage signs so i put it through a quick url decode and got the Flag as @BLU3T3AM$0LDI3R.

Then, download testdisk. Then sudo testdisk recoverfiles.dd.

Then, create log. Then, select dd file. Then all the original file names were shown and the answer for the gif was vanilla.gif.
![Screenshot from 2022-09-18 22-51-24](https://user-images.githubusercontent.com/24385029/204000091-ddcdf266-7670-4296-bbb1-87fb042d8635.png)
