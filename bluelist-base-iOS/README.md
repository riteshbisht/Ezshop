Sample: bluelist-base-iOS
===

The bluelist-base-iOS sample is the base version of BlueList, a simple grocery list application.  In bluelist-base-iOS, the items do not persist to a mobile backend. If you want to persist items to a mobile backend, use the bluelist-mobiledata-iOS sample.

This sample works with the Mobile Cloud, an application boilerplate that is available on [IBM Bluemix](https://www.ng.bluemix.net).  With this boilerplate, you can quickly incorporate pre-built, managed, and scalable cloud services into your mobile applications without relying on IT involvement. You can focus on building your mobile applications rather than the complexities of managing the backend infrastructure.


Downloading this sample
---
You can clone this sample from IBM DevOps Services with the following command:

    git clone https://hub.jazz.net/git/mobilecloud/bluelist-base

The bluelist-base-iOS sample will be located within the bluelist-base directory you just created.

Downloading the Dependencies
---

You can now download the dependencies for this sample using cocoapods!
This will enable you to skip the SDK download instructions in the article below.

First, install CocoaPods using the following command:

      sudo gem install cocoapods

Next, go to the folder containing the bluelist-base-iOS sample.  Then, install the
dependencies listed in your podfile using the following command:

      pod install


Running this iOS sample (bluelist-base-iOS)
---

You may now open the project's .xcworkspace file, and get started!

See the instructions in [Build an iOS app using the Mobile Data cloud service](http://www.ibm.com/developerworks/library/mo-ios-mobiledata-app/index.html) for more information about how to import this sample into your Xcode development environment and run the sample in a mobile emulator.
