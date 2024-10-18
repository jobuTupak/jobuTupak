Write Up Capture The Flag (CTF)


So, I've been given a ctf weekly challenge by the clurb. I'm here for it. 

![Image_Alt](https://github.com/jobuTupak/jobuTupak/blob/73eb51aabc5ecdcdaf72200c1f27da3822fee208/ctf%201.png)

-What do we have here...I opened the description first to see what's going on

![Image_Alt](https://github.com/jobuTupak/jobuTupak/blob/14e3d1dcd7f8321265c75e9b57aa146e370c5730/ctf%201%20a.png)

26 TIMES!? I wonder what kind of code it is... And the other file gives me a long encoded code... I tried looking through all of it and the code have all the 26 letters, and suddenly at the end of the code...

![Image_Alt](https://github.com/jobuTupak/jobuTupak/blob/14e3d1dcd7f8321265c75e9b57aa146e370c5730/ctf%201%20b.png)

So, it's a base64 encryption... Since it has been encoded 26 times, maybe we can reverse it 26 times.

![Image_Alt](https://github.com/jobuTupak/jobuTupak/blob/3770e6c85da7fd32274d13a7d5f86faab0c4862f/ctf%201%20c.png)

I just need to decode using base64 and copy the answer and put it back into the auto decode over and over again. I see some changes, almost there.

![Image_Alt](https://github.com/jobuTupak/jobuTupak/blob/cfa66e262c568b0d2df535fae18c485967fbaa73/ctf%201%20binggo.png)

BINGGO! all it needs is trust the process... I guess.
