# Valetudo Voice Prompts

Voice prompts for [Valetudo](https://github.com/Hypfer/Valetudo) open source software. These prompts can used on Dreame vacuum so may not work for other devices due to different filenames/prompts. Feel free to fork and use for other vacuums.

Other voice prompts will be added in future. First to kick off repo is Terminator voice (T2 folder)

How to Install :
1. Go to https://github.com/carefulcomputer/valetudo_voice_prompts/releases find the latest release. Then right click on file name T2.tar.gz and copy link. Save it in notepad or any text editor. No need to download the file, we just need the link.
2. From same release, click on md5sum.txt file and it will download to your computer. Open the file in any text editor and copy the value from that file. That is the md5 hash of zip file. Save it in notepad or any text editor. We will use it later.
3. Go to your Valetudo's user's interface. (Switch to new frontend if you are not already using new frontned from burger menu on top left).
4. Go to 'Robot settings'
5. In 'Voice pack management' enter following values
   * URL : Link saved from step 1
   * Language Code: T2
   * Hash: Value saved from step 2
   Click 'Set Voice pack'.


License: Due to upstream voice generator license these voices can only be used for personal purposes only. No commerical use.

If you want to make your own voice prompts, that is very easy !
Here are steps:

1) Refer to list of prompts compiled by @ccoors here https://github.com/ccoors/dreame_voice_packs/blob/main/sound_list.csv
2) Change the wordings to whatever you want your robot to say (for e.g. I removed all 'please' from T2 voice. Terminator will never say please :) ). Try to keep them close to original wordings since otherwise it will be hard to undrestand the actual robot status.
3) Now you can do it two ways -
  * Hard way-  Use https://vo.codes/ (or any other TTS service) to genreate sound files. Once you get the wave files from those services, you will need to transcode them to ogg format at mono, 16000hz. Once you have all ogg files, then tar.gz them , calculate md5 and upload to valetudo.
  * Easy way- Open an issue with all text prompts and the name the specific celebrity from https://vo.codes/ and I will generate all the voice prompts, md5 and release it here so everyone can use them.
