# setting-up-espeakng-mbrola-windows

I had to search all over the web for the reason why Espeak NG won't load MBROLA voices on windows.
So I hope this little repository will help someone and prevent them from spending time searching.

1. download https://github.com/user-attachments/files/19094349/mbrola_ph.zip, extract folder and place it into \eSpeak NG\espeak-ng-data\
2. download https://archive.org/details/MbrolaTools35 and install
3. download https://github.com/thiekus/MBROLA/releases/download/3.3/mbrola_build_3.3_rev2.zip and extract everything from Release to \eSpeak NG\
4. go to https://github.com/numediart/MBROLA-voices and download desired voices
5. place downloaded files to \eSpeak NG\espeak-ng-data\mbrola\ (if folder does not exist - create it)
6. now you can navigate to \eSpeak NG\ and run start espeak-ng.exe -v mb-en1 "Hello world!" to test it.

***NOTE***: mb-en1 here is just an example, use voice name from \eSpeak NG\espeak-ng-data\mbrola\ with mb- prefix.
