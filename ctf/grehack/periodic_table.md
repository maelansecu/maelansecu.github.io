---
layout: default
---

## Challenge statement

```I don't remember how I hid my key in this file, but I left myself all the necessary clues in this picture...```

Picture can be downloaded [here](https://cdn.discordapp.com/attachments/1043492406340882472/1043909462097924186/my_periodic_table.png)

## Resolution

The picture has some cases of the periodic table colored : Li, Sc and Bi, respectively in green, blue and red.
You can quickly deduct that this challenge is about LSB, and corresponding bits used to hide data are the 1st in green, 3rd in blue and 5th with red.

Using [StegOnline](https://stegonline.georgeom.net/), you can easily extract data :

![Screenshot_20221120_173817](https://user-images.githubusercontent.com/105165050/202914231-3c3247d2-b1e3-4542-93ad-f23f8fe8aefb.png)

Note the particular configuration of LSB : bit plane order used is GBR and not the usual RGB.

![Screenshot_20221120_173837](https://user-images.githubusercontent.com/105165050/202914274-3431a2e8-9fe2-4cb0-9b5f-12de713c4062.png)

And here is the flag : `GH22{LSB_h1dd1ng_c4N_b3_d0n3_1N_mult1pL3_w4ys}` !
