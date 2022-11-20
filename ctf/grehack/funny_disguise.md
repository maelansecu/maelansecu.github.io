---
layout: default
---

## Challenge statement

```I found this picture on a USB key I retrieved on the ground. Can you give me information about it?
I'm looking for the place, the year, and the name of the two artists in the photograph.
Flag format: GH22 {place_year_name1_name2}, with the names ordered alphabetically, everything in lowercase.
```

Picture can be downloaded [here](https://cdn.discordapp.com/attachments/1043492406340882472/1043909548743864460/picture.jpg)

## Resolution


First thing I've done, is to check the EXIF data thanks to [Aperisolve](https://www.aperisolve.com/) :

![Screenshot_20221120_164720](https://user-images.githubusercontent.com/105165050/202911832-46bf4231-bedc-457b-90bc-6e7801a6f4fa.png)

We can see a lot of useless informations, but one is quite useful : the author's name, Thom's Photography.
While searching for it, we can find 2 things :

- [A website page](https://www.thomsphotography.com/) that won't be of any use
- [A facebook page](https://www.facebook.com/thomsphotogrxphy)

When we scroll on the Facebook page, we can see a lot of cosplayers pictures, and then, the one we're looking for :

![Screenshot_20221120_164536](https://user-images.githubusercontent.com/105165050/202911811-30560141-218c-4eba-b32d-5a32a3c76a0d.png)

The picture has been taken during HeroFestival, in 2019. Its location is at Alpexpo, and we have the first part of our flag.
A little bit of more search to determine who's who with previous posts :

![Screenshot_20221120_165045](https://user-images.githubusercontent.com/105165050/202911886-3db7e764-b083-474e-b940-f0991cff58bd.png)

We can assume that Haneka Uta is not on the picture, because they're only mentionned here.
So our two targets are SISCosplays.

We only had to check their Facebook Page, where their artists name were :

![Screenshot_20221120_165403](https://user-images.githubusercontent.com/105165050/202912074-badb8fd1-5e33-4ef5-a712-ea2072fe04ca.png)

Bingo ~ 

The flag was : `GH22{alpexpo_2019_hisui_kuroe}` !
