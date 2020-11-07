# Math and other stuff

DCI resolutions add a bit more to the horizontal resolution of the frame compared to their normal non-DCI counterparts.

For example:
UHD 4K (non-DCI) full frame resolution is 3840x2160
DCI 4K full frame resolution is 4096x2160

DCI 4K is 256 pixels wider.

With some quick math, we can now get a DCI version of a regular resolution.

Formula: ![formula](http://www.sciweavers.org/tex2img.php?eq=DCI%20Width%20%3D%20input%20width%2B%5Cfrac%7Binput%20width%7D%7B15%7D%20&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0)

So if we wanted to get the DCI full frame version of 720p, we would do:

1280 + 1280/15 = 1365 (horizontal resolution)

So technically, the DCI full frame resolution for 720p would be 1365x720 (this isn't official, though)
