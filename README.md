# MDPIC
<p align="center" class="has-mb-6">
<img class="not-gallery-item" height="48" src="https://raw.githubusercontent.com/skycity233/MDPIC/master/logo.ico">
<br> Use Github Build Your Own Markdown Picture Server.
<br>
<a href="https://github.com/skycity233/MDPIC">Preview</a> |
<a href="https://github.com/skycity233/MDPIC/releases/download/v1.0/MDPIC.rar">Download</a>
<br>
</p>

### :cd: Installation
Download and extract or fork this & git clone your own frok repository, and that's it!

```shell
git clone [your froked repository]
```
Once started, please fill the configuration files named [config.yml](https://github.com/skycity233/MDPIC/blob/master/config.yml).

### :gift: How To Use

After you download or git clone the fork repository you will get this in you own folder

![folder](https://raw.githubusercontent.com/skycity233/MDPIC/master/images/image_2.png)

Make sure to edit the config.yml first.

- If got the full python environment, you can run the script by:

```shell
python mdpic.py
```

- If not, you just need to click the mdpic.exe to run the script.

**When the script running background**

1. Copy a image from the website or take a screenshot by some other screenshot script (eg. Snipaste)
2. Press Ctrl + M to upload your images in the clipboard to your github page
3. The image's URL will send to your Clipboard, just paste it in your Markdown file.

🔨 Improvement

I fail to hide the console, I tried the `pyinstaller -F -w` to build the .exe file, but it wasn't work, so I have to remove the option `-w` to build successfully.

If anyone got a suggestion can fix it, just Email me or make a pull requests. Thks! :smile:
