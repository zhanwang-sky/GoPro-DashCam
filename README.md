# GoPro-DashCam
Use a GoPro as a dash camera.

### Step I. Download and install [GoPro Labs](https://gopro.com/en/us/info/gopro-labs) firmware
[HERO12 Black](https://media.githubusercontent.com/media/gopro/labs/master/docs/firmware/lfs/LABS_HERO12_02_20_70.zip)<br>
[HERO11 Black](https://media.githubusercontent.com/media/gopro/labs/master/docs/firmware/lfs/LABS_HERO11_02_30_70.zip)<br>
[HERO10 Black](https://media.githubusercontent.com/media/gopro/labs/master/docs/firmware/lfs/LABS_HERO10_01_60_70.zip)<br>

### Step II. Reset all metadata
`!RESET`

### Step III. Load `dashcam` script at boot
`*BOOT="!Ldashcam"`

### Step IV. Save the following commands as a script called `dashcam`
`!SAVEdashcam=!C64oC5mV5!S`

explanation:<br>
`!C64`: Clear up to 64GB of data, the older files will be removed.<br>
`oC5`: Power off after 5 mins.<br>
`mV5`: Video mode 5 (Basic mode).<br>
`!S`: Start capture immediately.<br>

Now, restart your GoPro, it will automatically capture video using Basic mode.
