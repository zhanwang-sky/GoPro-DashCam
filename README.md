# GoPro-DashCam
Use GoPro as a dash camera.

### Step I. Download and install [GoPro Labs](https://gopro.com/en/us/info/gopro-labs) firmware

### Step II. Reset all metadata
`!RESET`<br>
![RESET](images/RESET.png)

### Step III. Load `dashcam` script at boot
`*BOOT="!Ldashcam"`<br>
![BOOT](images/BOOT.png)

### Step IV. Save the following commands as a script called `dashcam`
`!SAVEdashcam=!C64oC5mV!S`<br>
![SAVE](images/SAVE.png)

explanation:<br>
`!C64`: Clear up to 64GB of data, the older files will be removed.<br>
`oC5`: Power off after 5 mins.<br>
`mV`: Video mode.<br>
`!S`: Start capture immediately.<br>

Now, restart your GoPro, it will automatically capture video.
