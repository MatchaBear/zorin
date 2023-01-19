
# zorin

## zorin os important tweaks

- change display settings to use external monitor by default when boot-up and user login:

https://www.youtube.com/watch?v=aCNBj8WrqDI

vi ~/.profile

add below line:

>
> xrandr --output DP-3 --auto --right-of DP-0
>

subsequently after

>
> xrandr
>

src: <https://forum.zorin.com/t/persistent-mirrored-display-reverting-from-joined-how-to-stop/21273/12>
<https://forum.zorin.com/search?q=display>
