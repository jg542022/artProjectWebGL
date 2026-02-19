# Instructions for running.

Only tested in chromium-based browsers like chrome and arc. Requires mouse/trackpad, touch not supported.

Most browsers stop you from accessing external files when running locally, so you should use a webserver (still just running on your machine, but now your browser treats it like a normal webpage). Below are instructions to do that.

[Install Node](https://nodejs.org/en/download)

Install http server:
npm install http-server

Run this command in the webgl directory (use cd command to navigate directories in the terminal) to start the webserver:
npx http-server . -o -p 9999
