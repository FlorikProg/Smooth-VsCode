# Smooth-VsCode
If you want to make your cursor and typing smoother. Follow the steps below:

Open Visual Studio Code > Go to settings and type settings.json > and paste this code at the end of the file:

``` json
{
    "editor.cursorBlinking": "expand",
    "editor.cursorSmoothCaretAnimation": "on",
    "editor.fontLigatures": true,
    "editor.mouseWheelZoom": true,
    "editor.lineHeight": 1.5,
    "editor.rulers": [
        99
    ],
}
```
