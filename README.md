# Android Studio Environment Setup

The first thing you will want to do is go and download:

[Android Studio](https://developer.android.com/sdk/installing/studio.html)

[Java JDK 8u25](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)

Install both and try to start Android Studio, if it doesn't open you will need to add the jdk to your path.
Once Android Studio opens you need to download the Android SDK.

You can open the sdk manager from a couple different ways. You can click the android
in a box icon in the bar at the top of Android Studio if you are in a project. It looks like this:

![open sdk manager 1](Images\2014-10-15_20-24-10.png)

Another way is to go from the open projects window. When it first comes up click
configure, and then sdk manager like so:

![open configure](Images\2014-10-15_20-32-22.png)
![open sdk manager 2](Images\2014-10-15_20-33-42.png)

The final option is to open it from your explorer (which on windows is sometimes
required due to some permission issues). Find the locationyou install Android Studio
and navigate to there. Inside you should see an sdk folder. From there navigate
to sdk\tools and find the android.bat file. Run that as admin to fix the permissions issue.


Once you are in the sdk manager you should see a check list, something like this:

![sdk manager](Images\2014-10-15_20-38-10.png)

In here you need to install all of the tools and all of the extras. (located at
the top and bottom) Also you need to get the api levels. For this I would recommend
api levels 18 through 20 and your check list should look something like this:

![apis 18-20](Images\2014-10-15_20-42-30.png)

You can uncheck 4.4W since that is for Android Wear, and also the Glass Developer Preview
listed in api level 19. I also recommend unchecking all the samples (unless you are going to
use them) since they take awhile to download, and quite a bit of space. When you select
install just go through and accept the permissions and let them all install.

Once finished, go back to your open projects window for android studio and click open project.
You need to then navigate to where the project folder is located on your drive and it should
show and android symbol letting you know it recognizes the project. It should look something like this:

![open window](Images\2014-10-15_20-50-24.png)

Just highlight it and click okay. It will open the project and start grabbing gradle.
Let gradle finish configuring (downloading dependencies, and iteself) and once finished
you are good to start running the code.
