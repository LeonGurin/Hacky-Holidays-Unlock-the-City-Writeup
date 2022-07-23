**[25 POINTS]** *FOR YOUR EYES ONLY*

Are you able to see what was being sent?
___
If we open up the file inside `Audacity` and switch to the spectrogram view we can easily identify the flag as:
> CTF{Tagalong}

![img0](https://github.com/LeonGurin/My-CTF-challenge-Writeups/blob/main/Hacky%20Holidays%20-%20Unlock%20the%20City/AUDIBLE%20TRANSMISSION/images/img0.png)

**[75 POINTS]** *CODE*

We think it may have something to do with a code, can you find it?
___
Reversing the audio and listening to it we can hear some language being spoken. Writing the words `apat sham apat apat` into google translate with the `detect language` option reveals to us that the language is Filipino.

Translating the audio in google translate with the microphone option reveals the translation:
> get this code the flag is 649 444

and that's our flag.
