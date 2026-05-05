
#  PWNTERAS

## MISC : 3g4m1_n4_t0N


## Description
Chupapija es un perro muy guapo y popular entre todas las perritas de su condado, es un agente secreto pero no recuerda su nombre :c
¿Puedes yudarlo a encontrarlo? c:

hint: zip

## Files

- Maybe ust a .jpeg image lol
<img width="195" height="258" alt="noimage" src="https://github.com/user-attachments/assets/45894bcb-7686-47a8-b91b-8bd0fe4c5889" />

## Analysis

You can only see a dog in an image. But this is not an image, maybe is something else.



## Solution

if you put the `file` command is going to tell you is a jpeg image, using `exiftool` you will see that the author of the photo is FLUFF AGENT... 
And then what?

If you try to list files with
 `unzip -l imagen.jpg`
then you will see a list of many files named file_0*.txt 

Try to unzip it! `unzip imagen.jpg -d reto`

And try to find the author (FLFFAGENTTT) if you have luck youll find it

So you don't know how to use grep just type `grep -rn "fluff_4g3nt" challenge_files` and there is the flag. ☺

### Flag: pwnteras{u_f0und3d_th3_und3rcov3r_fluff_agent}

