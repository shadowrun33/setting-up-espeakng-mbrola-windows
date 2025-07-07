*I had to search all over the web for the reason why Espeak NG won't load MBROLA voices on windows.
So I hope this little repository will help someone and prevent them from spending time searching.*

#How to set up MBROLA to use MBROLA voices in Espeak-NG on windows

1. Download https://github.com/user-attachments/files/19094349/mbrola_ph.zip, extract folder and place it into `\eSpeak NG\espeak-ng-data\`
2. Download https://archive.org/details/MbrolaTools35 and install
3. Download https://github.com/thiekus/MBROLA/releases/download/3.3/mbrola_build_3.3_rev2.zip and extract everything from Release to `\eSpeak NG\`
4. Go to https://github.com/numediart/MBROLA-voices and download desired voices
5. Place downloaded files to `\eSpeak NG\espeak-ng-data\mbrola\` (if folder does not exist - create it)
6. Now you can open command line, navigate to your `\eSpeak NG\` and run `start espeak-ng.exe -v mb-en1 "Hello world!"` to test it.

***NOTE***: `mb-en1` here is just an example, use voice name from `\eSpeak NG\espeak-ng-data\mbrola\` with `mb-` prefix.

Alternatively, you can download neccessary files directly from this repository.


*Information and files gathered from this issues: https://github.com/numediart/MBROLA/issues/46#issuecomment-2701729556, https://github.com/espeak-ng/espeak-ng/issues/723#issuecomment-2701825064*

*So, this repository exists solely thanks to https://github.com/lethanner*
