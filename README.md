sample-apps-ios-cocoapods
=========================

A sample iOS app which uses CocoaPods

# Notes

* with Xcode 6.0.1 and CocoaPods 0.34.2 I had to set "Build Active Architectures Only" to *No* in the Pods project!
	* more info: [http://stackoverflow.com/a/22336208/974381](http://stackoverflow.com/a/22336208/974381)
	* this means the Pods project file at *SampleAppWithCocoapods/Pods/Pods.xcodeproj/project.pbxproj* have to be included in the repository