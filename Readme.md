# Guide for `"MORT"` 
> ## Real-time OCR translator for any game.



>This is a draft tutorial write for `MORT 1.253` , and the details will be added later. If you have any questions, please feel free to contact me.
![MORT](https://i.imgur.com/Xrh72F2.png)
## Downloading and Installing the Software
1. Go to the MORT project page on GitHub: [GitHub - killkimno/MORT](https://github.com/killkimno/MORT)
2. Navigate to the [Releases](https://github.com/killkimno/MORT/releases) page and download the latest release.
![GitHub Release Page](https://i.imgur.com/sPGjV3e.png)
3. Once downloaded, extract the files and run the `MORT.exe` file.

## Setting Up the Software

1. Start with quick setting with 'Japanese Game'.
![Quick Setup](https://i.imgur.com/uVyXqgE.png)
- Choose the game dialogue font color type, or select the default and you can choose the font color later.
![pick the game dialogue font color](https://imgur.com/DnTiQ1T.png)
- Setting OCR Area
![OCR area setting](https://imgur.com/F85fKo8.png)
![OCR area setting](https://i.imgur.com/gXPx1Er.png)
- click close to end the quick setting.
![close](https://i.imgur.com/hFFDDP5.png)

2. Done! After the quick setup just click 'Translate' button, the software is fully automatic and captures text in real-time.
   
![translate button](https://i.imgur.com/GMLVadY.png)
![done](https://i.imgur.com/UO89ECV.jpg)

 
> Tip:
>  - The program defaults to use `Windows OCR` to recognize the screen, so you need to have the corresponding language pack installed on your Windows. If you don't know how to do it, please refer to [Troubleshooting](https://github.com/jctneko/MORT-OCR-Translator-Tutorial#troubleshooting).
>  - You may have to adjust your game dialogue opacity to 100% for better OCR result.
>  - You can setting the Text to speech by toggling the 'TTS' option in the settings.

## Image Adjust setting for ORC
 Adjusting the image before OCR for better result.

 Generally, the default OCR works quite well. However, if the OCR results are not satisfactory, you can try the options here to improve the performance.

- adjust by thresehold
![Dialogue thresehold adjust](https://i.imgur.com/cOCZpmp.jpg)

- adjust by color 
![Dialogue color adjust](https://i.imgur.com/h2xJk0K.jpg)

## Using with DeepL
1. If you prefer to use DeepL for translation, ensure that the status is 'available'.
![DeepL status check](https://i.imgur.com/ghrPPDm.png)
2. The process chain would look like this: screen -> windows OCR -> MORT -> Edge (background) -> result
3. DeepL requires the Edge browser to work in the background.
4. You can run the game with any browser, because it just captures the screen.

## Troubleshooting
1. Check the [System Requirement](https://github.com/killkimno/MORT#system-requirement)
2. Does the OCR language selection not have a Japanese option?? 
- to use Windows OCR, you'll need to install the Japanese language pack in your Windows operating system settings.

    ![windows japanese language pack](https://i.imgur.com/DlqDD88.png)

    [youtube: install the japanese language pack in windows](https://www.youtube.com/watch?v=Iq8YERqmRbg)

3. If MORT is not capturing the text, check the settings and ensure the software is set to your specific browser.
![process monitoring](https://i.imgur.com/UqeusNy.png)
4. If you are still having trouble, you can change the OCR engine to a different one under the OCR settings.

>Remember, this is an open-source tool that is continually being updated. Please report any issues or suggestions to the developers via the GitHub page. This tool is a great way to get real-time translations for games or other applications that do not have built-in translations.
