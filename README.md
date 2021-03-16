# cloud-amiga

This is a project to get an Amiga running in the browser.  I got dosbox to work OK, but fs-uae give GL and/or display errors.  Next up is to investigate another linux emu or another windowmanager, or different linux distro (I tried Ubuntu on OCI so far).

Build the dockerfile with:

$ docker build -t myamiga .

Then run the image with something like:

sudo docker run --name wi-amiga -p 8080:80 myamiga &

Then point your browser to http://localhost:8080/vnc.html

based on https://github.com/theonemule/dos-game
