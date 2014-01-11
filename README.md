iOS-Development-Intro
=====================

Getting started with iOS Development
-----------------------------------

Requirements to get started:

1. Mac computer running OS X 10.7 (Lion) or later. Preferably OS X 10.9 (Mavericks).
2. Xcode 5
3. iOS SDK 7

[Apple's Setup Notes](https://developer.apple.com/library/ios/referencelibrary/GettingStarted/RoadMapiOS/index.html#//apple_ref/doc/uid/TP40011343)

Note - All requirements are free, with the exception of the Mac computer. The only drawback is you will not be able to run your App on a physical device until you register as an iOS Developer with Apple. This cost is currently $99/year.

To get started the simulator will work just fine.


Once you are all set and meet the requirements follow the steps below.

1. Check for OS X updates.

   It is best to make sure your OS X install is up to date.
   
   <img src="https://raw2.github.com/mrkd/iOS-Development-Intro/master/images/OSX-AppStoreUpdates.png" alt="Drawing" style="width: 500px;"/>

2. Install Xcode 5 from the OS X App Store.
   
   <img src="https://raw2.github.com/mrkd/iOS-Development-Intro/master/images/xcode-icon.png" alt="XCode Icon" style="width: 128px;">
   * Xcode 5 is a little over 2GB download.
   * Xcode will be installed to: `/Applications/XCode.app`
3. Once the download is complete open XCode


Hello Xcode and iOS Development
-------------------------------

Now that XCode is installed on your Mac we can start with the Hello World for iOS Development. XCode makes this extremely easy for us.

<img src="https://raw2.github.com/mrkd/iOS-Development-Intro/master/images/welcome-to-xcode.png" alt="welcome-to-xcode" style="width: 500px;"/>

1. Open XCode
   * You should see the 'Welcome to Xcode window'
   * Note if you are not running OS X 10.9 ()Mavericks) the 'command line tools' will 
   	 not be installed automatically for you. You will need to go to the menu bar 
	 under Xcode->Preferences and select the Downloads tab.
   * In the Components section click the download arrow to the right to install and download
     the Command Line Tools.
     
     <img src="https://raw2.github.com/mrkd/iOS-Development-Intro/master/images/xcode-install-command-line-tools.png" alt="install-command-line-tools" style="width: 400px;"/>
     
   
   
2. Click 'Create a new Xcode project'
3. Select the 'Single View Application' template for the new project.

   <img src="https://raw2.github.com/mrkd/iOS-Development-Intro/master/images/choose-project-template.png" alt="choose-single-view-application" style="width: 500px;"/>
4. Next will be the 'Choose options' window.
   * The 'Company Identifier' will be a part of your Application's 'Bundle Identifier'. The bundle identifier is almost like the executable's name, in that it tells iOS which application this is. If the bundle identifier changes and you install the app it is just like installing a whole new application.
   *  The class prefix is recommended to be 3 characters. Here I just chose 'MRK' for 'Mark'. This is Objective C's workaround for not having namespaces.
   * We will leave the devices selection as 'Universal' so the app will run on iPhone and iPad devices.
5. Next choose a location to save the project at. I usually create a `~/workingDirectory` to keep any projects I am actively developing.
   * Note: Leave the 'Create git repository on My Mac' checked. This will automatically setup the project
     directory as a git repository for us.
5. You should now have your new project in Xcode open. Press the Play button in the upper left of the window to build and run the project.

   <img src="https://raw2.github.com/mrkd/iOS-Development-Intro/master/images/new-project-xcode.png" style="width: 500px;"/>

   * You may be prompted to enable developer mode on your Mac. Go ahead and Enable this.
6. Once your project builds Xcode will start the iOS simulator, install your app, and run it.
   * You should now see your application running in the simulator. For now this is simply a white window.
   
   <img src="https://raw2.github.com/mrkd/iOS-Development-Intro/master/images/app-running-in-simulator.png" alt="app-running-in-simulator" style="width: 500px;"/>


