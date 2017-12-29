# Cipher

Solutions for http://www.gamemastertips.com/cipher/cipher.htm

## TOC

| Level | URL | Password | 
|---:|:---|:---|
| 1 | http://www.gamemastertips.com/cipher/begin/clickthedoor.htm | | 
| 2 | http://www.gamemastertips.com/cipher/omgits/level2.htm | |
| 3 | http://www.gamemastertips.com/cipher/omgits/level3.htm | |
| 4 | http://www.gamemastertips.com/cipher/omgits/braggart.htm | |
| 5 | http://www.gamemastertips.com/cipher/brick/wall.htm | `trojan` |
| 6 | http://www.gamemastertips.com/cipher/brick/hollow.htm | |
| 7 | http://www.gamemastertips.com/cipher/brick/abolished.htm | |
| 8 | http://www.gamemastertips.com/cipher/creppy/ | `concealed` |
| 9 | http://www.gamemastertips.com/cipher/creppy/agility.htm | |
| 10 | http://www.gamemastertips.com/cipher/creppy/cabbage.htm | |
| 11 | http://www.gamemastertips.com/cipher/pippity/ | `decade` |
| 12 | http://www.gamemastertips.com/cipher/pippity/mix | |
| 13 | http://www.gamemastertips.com/cipher/pippity/invention |
| 13.5 | http://www.gamemastertips.com/cipher/pippity/madman | |
| 14 | http://www.gamemastertips.com/cipher/pippity/puyrruh.htm | |
| 15 | http://www.gamemastertips.com/cipher/pippity/dissolve | | 
| 16 | http://www.gamemastertips.com/cipher/monkey/wrench.htm | `wrench` (username: `monkey`)| 

## 1

Click the door to go to level 2.

## 2 

Click the image and read the alert and then notice the title "URL?".

Change url from `level2` to `level3`.

## 3

See the source:

```
<!--go to braggart.htm-->
```

## 4

Decode this binary string `011101000111001001101111011010100110000101101110` with some tool like https://www.qbit.it/lab/bintext.php and you will get `trojan`

Click image and input `cipher` and `trojan` to go to next level.


## 5

See the title and realize something hidden in the black-background page.

Either see the source code or select all in the page to find out string `hollow.htm`.

## 6

Source code says:

```
<!--Why 'a?' Why not something else?-->
```

so change from `a` to `b` in the image file name to load the next image and so on and so forth and concatenate the letters to have `abolished`.

## 7 

Title `Illuminate the darkness...` implies that to process the image (such as thresholding).

## 8

See the source:

```
<!--gif me something else-->
```

so change the image file extension to `gif` and extract each frame of the GIF file with some tool like https://ezgif.com/split and have several numbers.

Considering the page title `ASCII`, decode the number and have the word for next level.

## 9

See the source:

```
<!--something amiss?-->
```

and notice the image file name is `screen8.jpg` but it's level 9. 

So change it to `screen9.jpg` and decode the notes to have `CABBAGE`.

## 10

See the title "This level is HEXed" and the commment below it:

```
<!--in a colorful sort of way-->
```

Pick hex color from the image to have the next word.

## 11

Roman number for 1009 (watermarked in the image) => MIX

## 12

Simply use this tool http://www.hanginghyena.com/solvers_a/cryptogram-helper and tried out each word

(The right way is, with the mappings given, to look at keyboard)

## 13 

Given the list of years, find out which month has the Nth Black Friday. 

Concatenate the initials of each month -- `madman`

## 14

Just like the WAV file name and comment indicate, the sound should be reversed and sped up. 

## 15

The image source is actually a txt file. 

Inside the txt file, it's a base64 string. 

Decode it (using tool such as https://www.base64decode.org/) and you will see `/monkey/wrench.htm`.
