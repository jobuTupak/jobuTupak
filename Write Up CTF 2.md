- Now that we have done the first CTF, we moved on to the next which is the last CTF for the week

The folder was given and there are 3 files and 1 folder directory.

![Image_Alt](https://github.com/jobuTupak/jobuTupak/blob/ef666ea5c1950d9f4ef74edf8a6cafa5e4684a1d/ctf%202%200.png)

Since there was sha256.txt file in it. Then I supposed this CTF is about basic sha256 checksum encryption.
What about the decrypt.sh file...

![Image_Alt](https://github.com/jobuTupak/jobuTupak/blob/ef666ea5c1950d9f4ef74edf8a6cafa5e4684a1d/ctf%202%20f.png)

The openssl will generate the flag file... I do not know anything about the "catmeow" (is that normal? how does it execute though) as a command though... ANYWAY

let's take a look inside "penting" folder.

![Image_Alt](https://github.com/jobuTupak/jobuTupak/blob/ef666ea5c1950d9f4ef74edf8a6cafa5e4684a1d/ctf%202%20c.png)

It is checksum. All of the files in the directory contain encoded text. 
Hence, we need to find the right integrity as the encryption file.
Let's take a look into one of the files...

![Image_Alt](https://github.com/jobuTupak/jobuTupak/blob/ef666ea5c1950d9f4ef74edf8a6cafa5e4684a1d/ctf%202%20d.png)

Before we do allat, what about the sha256.txt file...

![Image_Alt](https://github.com/jobuTupak/jobuTupak/blob/ef666ea5c1950d9f4ef74edf8a6cafa5e4684a1d/ctf%202%20e.png)

It has the same format as one of those files.
Let's do the comparison in each files inside the directory with the Sha256.txt file. One by One.

IM JOKING, that would take FOREVER. Just copy and paste the sha256 file text and use this command instead

![Image_Alt](https://github.com/jobuTupak/jobuTupak/blob/ef666ea5c1950d9f4ef74edf8a6cafa5e4684a1d/ctf%202%20g.png)

BOOM, you get straight to the correct file

Then, we can continue use the decrypt.sh file to get the flag file.

![Image_Alt](https://github.com/jobuTupak/jobuTupak/blob/ef666ea5c1950d9f4ef74edf8a6cafa5e4684a1d/ctf%202%20h.png)

Let's check back the CHALL directory.

![Image_Alt](https://github.com/jobuTupak/jobuTupak/blob/ef666ea5c1950d9f4ef74edf8a6cafa5e4684a1d/ctf%202%20i.png)

since I have no idea what type of file is, I'll check a bit...
It's a ASCII text, so I think I'll just dive in.

![Image_Alt](https://github.com/jobuTupak/jobuTupak/blob/ef666ea5c1950d9f4ef74edf8a6cafa5e4684a1d/ctf%202%20j.png)

SETTLE! The deeds are done.
