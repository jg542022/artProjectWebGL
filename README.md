# Uncanny Instrument
###### by Jack Gibilisco


*Tested and works in firefox (gecko-based), chrome/arc (chromium-based), and safari (webkit-based).*

### Controls
**Trackpad:**
Click inside the webpage to capture mouse

One finger drag  – instrument
One finger click – toggle drums
Two finger drag  – look
Two finger zoom  – move
Two finger click – reset

**Mouse:**
Same as trackpad except

Scroll        – look
Ctrl + Scroll – move

**Keyboard:**
Esc – regain mouse control
p   – mute all sounds

**Mobile (touch):**
Same as trackpad except no drums or reset or zoom or keyboard controls

### Run Instructions

Most browsers stop you from accessing external files when opening the file on your computer, so you should use a webserver (still just running on your machine, but now your browser treats it like a normal webpage).
You may not need to do this for the kiosk app if it uses a webserver internally.

Below are instructions to use a local webserver.

[Install Node](https://nodejs.org/en/download)

Install http server:
`npm install http-server`

Run this command in the webgl directory (use `cd` command to navigate directories in the terminal) to start the webserver:
`npx http-server . -o -p 9999`

### Misc

If you can't figure it out, I have it working at [jackgibilisco.com/artprojectwebgl](https://jackgibilisco.com/artProjectWebGL/)
If I make any updates, the most up to date version will be on my [github](https://github.com/jg542022/artProjectWebGL)
