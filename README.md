# OSFMSaveGen
It's like https://solsticesavegen.rkevin.dev/, but in ASP.NET (not really).

## Building
If someone can tell me how to automate this, *please* tell me.

1. Clone the project in Visual Studio.
2. Go to the Solution Explorer, and right click the OSFMSaveGen project.
3. Go to "Publish".
4. Click the "Publish" button, and wait until it finishes.
5. Click "Open folder". Run OSFMSaveGen.exe from there.
6. Go to this URL: https://127.0.0.1:5000
7. Press <kbd>Ctrl</kbd>+<kbd>S</kbd>.
8. Save as a complete HTML, and put in a directory. Make sure it is named "indexa.html" for this.
9. Rename "indexa.html" to "index.html". Ignore the warnings.
10. Drag "bootstrap.min.css" out of the folder next to index.html.
11. Open index.html with Notepad, and replace "/indexa_files" with nothing.
12. Copy images.jpg and favicon.ico from wwwroot to the directory with index.html.
13. You are done.
