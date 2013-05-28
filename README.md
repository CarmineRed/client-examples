###Download Instructions for Chartboost Sample Projects

In this repo, you'll find two Chartboost example integrations: one for iOS games, and one for apps on the Android side. To get started, hit the **ZIP** button to download the repo:

<img src="https://s3.amazonaws.com/chartboost/help_assets/client-examples1.jpeg" />

You'll get a folder that includes both platforms' projects; after unzipping, keep the folder you need and discard the other. After that, read on for platform-specific installation instructions.

---
#####Installing iOS Sample Project in Xcode

1. Fire up Xcode and open the **iOS** folder included in the .ZIP archive
2. Navigate to the **ExampleAppAppDelegate.m** file by expanding the menus shown below:

<img src="https://s3.amazonaws.com/chartboost/help_assets/client-examples2.jpeg" />

This file contains the Chartboost code you'd add to AppDelegate.m in your own game &ndash; you can configure it with your App ID (`cb.appId`) and App Signature (`cb.appSignature`) to test the Chartboost integration independent of your code. 

When run in Simulator or on an iOS device, the project can display any interstitials or More Apps pages set (via the Chartboost dashboard) to run in your game; it's a great way to debug problematic campaign logic.

---
#####Installing Android Sample Project in Eclipse
