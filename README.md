# tetctf2024misc
                            **TET & 4n6 misc(cannot solve but I write what i did)**

## Description:
/img

## What I did:

First I downloaded the file in this challenge and unzipped some file inside.
/img
/img
Then after I unzip the zip file I got raw file and I open it with terminal using strings and see the flag 2 and other fake ip and port(which I think is the IP that I am finding)
/img
/img
So i saw .ad1 file so I researched and find that can use FTK imager to open and extract so I downloaded it but it was .exe file so I just downloaded wine using brew
```
$brew install --cask xquartz
$brew install --cask wine-stable
```
so I open the ftk imager
/img
click the image file and choose the ad1 file
/img
and you see the directory. Then I just downloaded all the files and look for something that looked like malware and I found this thing that has malware in the file name
/img
I thought that was malware but when I researched it, it a safe one so I researched more

After a few hours, I found the mimikatz file (Mimikatz is a tool that is commonly used by hackers and security professionals to extract sensitive information, such as passwords and credentials) and other files that .lnk(windows shortcut). I see that inside the files jave some directories that point to some docx, zip,... but I don't know what to do.
/img
/img

Then I found some other log file but I had no idea about how to use it.
/img
After that, I think that there is some file on the directory in .lnk files so I think I need to recovery file and try some.I download a tools name Foremost and start to recovery file but there is nothing again.
/img

#The last things I do
So I just research again and find [volatility3](https://volatility3.readthedocs.io/en/stable/)




