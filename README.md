# cloud-amiga

This is a project to get an Amiga running in the browser.  Build the dockerfile with:

$ docker build -t myamiga .

Then run the image with something like:

sudo docker run --name wi-amiga -p 8080:80 myamiga &

based on https://github.com/theonemule/dos-game
