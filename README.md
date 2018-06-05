# Google Desktop Apps for Mac OS X
We all use Google Apps everyday-Docs, Sheets, Gmail, Drive, etc.

Wouldn't it be nice to have your Gmail as an application that can remain open without needing to load Chrome and navigate to Gmail? Well that is the purpose of creating these various desktop Google Apps.

The first idea for this came from [/u/chriskol](https://github.com/chriskol) who created the first Google Docs and Keep versions. I discovered his github page when I realized that Google took Google Keep off the Chrome Web Store as an app to use on your desktop, opting to just make it available in the browser. I brought his code for Docs and Keep over to this repo to put everything in one centralized place.

Below is a list of all the apps currently available and instructions on how to download them. The quickest way to get them is to just head over to a site that was created to make them super easy to download: [**Google Apps for Mac**](https://www.googleappsformac.com).

# List of Google Apps Available
**Core Google Apps**
* [Google](https://github.com/landek/Google-Desktop-Apps-for-Mac-OS-X/tree/master/Google)
* [Gmail](https://github.com/landek/Google-Desktop-Apps-for-Mac-OS-X/tree/master/Gmail)
* [Inbox](https://github.com/landek/Google-Desktop-Apps-for-Mac-OS-X/tree/master/Inbox)
* [Drive](https://github.com/landek/Google-Desktop-Apps-for-Mac-OS-X/tree/master/Drive)
* [Maps](https://github.com/landek/Google-Desktop-Apps-for-Mac-OS-X/tree/master/Maps)
* [Web Store](https://github.com/landek/Google-Desktop-Apps-for-Mac-OS-X/tree/master/Chrome%20Web%20Store)

**Google Drive-Associated Apps**
* [Docs](https://github.com/landek/Google-Desktop-Apps-for-Mac-OS-X/tree/master/Docs)
* [Sheets](https://github.com/landek/Google-Desktop-Apps-for-Mac-OS-X/tree/master/Sheets)
* [Slides](https://github.com/landek/Google-Desktop-Apps-for-OS-X/tree/master/Slides)
* [Forms](https://github.com/landek/Google-Desktop-Apps-for-Mac-OS-X/tree/master/Forms)

**Calendar, Notes, & To-Do Apps**
* [Calendar](https://github.com/landek/Google-Desktop-Apps-for-Mac-OS-X/tree/master/Calendar)
* [Keep](https://github.com/landek/Google-Desktop-Apps-for-Mac-OS-X/tree/master/Keep)
* [Tasks](https://github.com/landek/Google-Desktop-Apps-for-Mac-OS-X/tree/master/Tasks)

**Entertainment & Fun, & Education Apps**
* [Youtube](https://github.com/landek/Google-Desktop-Apps-for-Mac-OS-X/tree/master/Youtube)
* [Photos](https://github.com/landek/Google-Desktop-Apps-for-Mac-OS-X/tree/master/Photos)
* [Google Music](https://github.com/landek/Google-Desktop-Apps-for-Mac-OS-X/tree/master/Music)
* [Youtube Kids](https://github.com/landek/Google-Desktop-Apps-for-Mac-OS-X/tree/master/Youtube%20Kids)
* [Express](https://github.com/landek/Google-Desktop-Apps-for-Mac-OS-X/tree/master/Express)

**Educational Apps**
* [Classroom](https://github.com/landek/Google-Desktop-Apps-for-Mac-OS-X/tree/master/Classroom)
* [Scholar](https://github.com/landek/Google-Desktop-Apps-for-Mac-OS-X/tree/master/Scholar)
* [Earth](https://github.com/landek/Google-Desktop-Apps-for-Mac-OS-X/tree/master/Earth)

**Business & Data Apps**
* [Cloud Console](https://github.com/landek/Google-Desktop-Apps-for-Mac-OS-X/tree/master/Cloud%20Console)
* [Blogger](https://github.com/landek/Google-Desktop-Apps-for-Mac-OS-X/tree/master/Blogger)
* [Analytics](https://github.com/landek/Google-Desktop-Apps-for-Mac-OS-X/tree/master/Analytics)
* [Adwords](https://github.com/landek/Google-Desktop-Apps-for-Mac-OS-X/tree/master/Adwords)
* [Adsense](https://github.com/landek/Google-Desktop-Apps-for-Mac-OS-X/tree/master/Adsense)
* [Optimize](https://github.com/landek/Google-Desktop-Apps-for-Mac-OS-X/tree/master/Optimize)
* [Surveys](https://github.com/landek/Google-Desktop-Apps-for-Mac-OS-X/tree/master/Surveys)

# How Do I Download One, Two, or All of them?
**You have two options:**
1. Download the apps from the website: [Google Apps for Mac](https://www.googleappsformac.com). (The easy option)
2. Download the .zip files from this github repo. (The barely harder option)

**Downloading from Github**
1. Download all the apps by downloading the folder in this repo called [**Download Apps**](https://github.com/landek/Google-Desktop-Apps-for-Mac-OS-X/tree/master/Download%20Apps)
--That folder has a .zip file that contains the app. Just un-zip and use!
2. Download individual apps by going to the individual folders for each application and download the .zip file in the folder. You do _not_ need to download the whole folder, just the .zip file, i.e. inside the Gmail folder you'd download [**Gmail.zip**](https://github.com/landek/Google-Desktop-Apps-for-Mac-OS-X/blob/master/Gmail/Gmail.zip) and unzip it.

**Click the image below to watch an ~60 second Youtube video on how to download, open, and modify your security settings to allow the apps to open**
[![How to Download](https://github.com/landek/Google-Desktop-Apps-for-Mac-OS-X/blob/master/youtubevideoscreenshot.png)](https://youtu.be/RQSgiJPDGfg)

# Opening Apps from an Unidentified Developer!
**Important final step to use the apps**
Due to the fact that I am an "unidentified" developer by Apple, you'll need to go into your "Security & Privacy" settings in System Preferences after unzipping and double-clicking on the app you download. Once in there, you'll see on the main page a little dialog box asking if you want to open the app anyway. The video below that shows how to download and open apps also shows how you navigate the security settings.

# How were these all made?
It is really simple. They are built with Javascript and MacGap, just one line of code to wrap the particular Google app in a window on your desktop. All made possible by [MacGap](https://github.com/MacGapProject/MacGap2). Build your own wrapper for an HTML5 app using instructions on [MacGap-rb](https://github.com/maccman/macgap-rb).

# Why don't you have X app available?
Most likely because it wouldn't play nice with the MacGap wrapper and/or it isn't too popular of an app. Feel free to send me an email or post a feature request in the issues for an app you'd like to see.

# I can't get X app to work on my computer?
Bummer. Just post the description of the problem in the issues and we'll figure it out.
