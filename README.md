PHP-GetImgFromClipboard
===
PHP-GetImgFromClipboard is a tool that allows you to get image on the clipboard(usually copy to the clipboard by taking a screenshot or copy from web page) and save it to an image file like jpg or png.

## Install
```bash
composer require xiebruce/php-get-image-from-clipboard:dev-master
```

## Requires
Actually, php can not get image on the clipboard directly, so this tool is rely on other tools.

### For macOS
For macOS, it rely on [pngpaste](https://github.com/jcsalterego/pngpaste), so you should install pngpaste first:
```
brew install pngpaste
```

### For Windows 10
For Windows 10, it's free to use, nothing need to be install.

### For Windows 7
For Windows 7, you need to update Powershell. Download Powershell update package "Win7AndW2K8R2-KB3191566-x64.zip" from here: [https://www.microsoft.com/en-us/download/details.aspx?id=54616](https://www.microsoft.com/en-us/download/details.aspx?id=54616), then update and restart.

Before update, you can check the Powershell version. Click "Start" menu on the bottom right corner, input "powershell" to search, then powershell shows up like this:
![Xnip2019-09-05_14-43-33](https://img.xiebruce.top/2019/09/05/f2dcd86c96d8459604797dd1396ceed2.jpg)

Click to open it and type this command:
```
$PSVersionTable
```

Now you can see, before update, the Powershell version is 2.0:
![Check Powershell version before update](https://img.xiebruce.top/2019/08/28/6d388e41f563be24a156c8cf6164fab7.jpg)

After update, the Powershell version is 5.0:
![Check Powershell version after update](https://img.xiebruce.top/2019/08/28/967284bf7f26ac192e859ffa73fec016.jpg) 


### For Linux Desktop
For Linux Desktop System(e.g. Ubuntu, Manjaro, CentOS etc.) , you need to install `xclip`.

On Ubuntu:

```bash
apt install xclip
```

I didn't test other Linux distributions, but it should be work.

