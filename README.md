#iOS-Development

List of iOS Frameworks, Articles, E-Books and more.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](http://doctoc.herokuapp.com/)*

- [Articles](#articles)
- [CocoaPods Libraries](#cocoapods-libraries)
    - [Data Process](#data-process)
    - [Database](#database)
    - [Networking](#networking)
    - [Passbook](#passbook)
    - [UI](#ui)
    - [My Podfile](#my-podfile)
- [Frameworks](#frameworks)
- [Debugging](#debugging)
- [E-Book](#e-book)
- [OTA Install URL Prefix](#ota-install-url-prefix)
- [Folder](#folder)
- [Xcode](#xcode)
    - [Packge Manager](#packge-manager)
    - [Plugin](#plugin)
- [Documentation](#documentation)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Articles
* [The Right Way to Ask Users for iOS Permissions](https://medium.com/p/96fa4eb54f2c)
* [The New York Times Mobile Team’s Objective-C Style Guide](https://github.com/NYTimes/objective-c-style-guide#notifications)
* [How to Generate Beautiful Apple-Style Documentation in Xcode 5](http://ios-blog.co.uk/tutorials/how-to-generate-beautiful-apple-style-documentation-in-xcode-5/)
* [Taming Xcode by Jay Thrash](http://cocoaheads.tv/taming-xcode-by-jay-thrash/)
* [讓 Xcode 專案易於版本控制的方法](http://nelson.logdown.com/posts/2014/01/27/easy-version-control-mechanism-for-xcode-projects)
* [The official raywenderlich.com Objective-C style guide.](https://github.com/raywenderlich/objective-c-style-guide#language)

# CocoaPods Libraries
### Data Process
* [NSDate-TKExtensions](https://github.com/mapedd/NSDate-TKExtensions.git) - Set of usefull categories for NSDate.

### Database
* [Realm](http://realm.io) - Realm is a modern data framework & database for iOS & OSX.
* [Realm-JSON](https://github.com/matthewcheok/Realm-JSON) - A concise Mantle-like way of working with Realm and JSON.
* [MagicalRecord](https://github.com/magicalpanda/MagicalRecord) - Super Awesome Easy Fetching for Core Data.

### Networking
* [AFNetworking](https://github.com/AFNetworking/AFNetworking.git) - A delightful iOS and OS X networking framework.

### Passbook
* [passbook](https://github.com/frozon/passbook) - Passbook gem let's you create pkpass for passbook iOS 6.

### UI
* [HexColors](https://github.com/mRs-/HexColors.git) - Easy HEX-Color and RGB-Color Handling for UIColor and NSColor as a drop in category. Former MLUIColorAdditions.

### My Podfile
```ruby
# Database
pod 'Realm'

# Networking
pod 'AFNetworking'

# UI
pod 'HexColors'
```

# Frameworks

# Debugging
* Pretty log
```c
#define NSLog(__FORMAT__, ...) NSLog((@"[%@] [Line %d] -> " __FORMAT__), [[NSString stringWithUTF8String:__FILE__] lastPathComponent] , __LINE__, ##__VA_ARGS__)
```

* Pretty Alert
```c
#define DebugAlert(__FORMAT__, ...)  { UIAlertView *alert = [[UIAlertView alloc] initWithTitle:[NSString stringWithFormat:@"Debug Message"] message:[NSString stringWithFormat:@"[%@] \n [Line %d] \n" __FORMAT__, [[NSString stringWithUTF8String:__FILE__] lastPathComponent], __LINE__, ##__VA_ARGS__]  delegate:nil cancelButtonTitle:@"Dismiss" otherButtonTitles:nil]; dispatch_async(dispatch_get_main_queue(), ^{ [alert show]; }); }
```


# E-Book
* [iOS Succinctly - FREE](http://ios-blog.co.uk/resources/ios-succinctly-free-e-book/)
* [iOS7 Day by Day](https://leanpub.com/ios7daybyday)

# OTA Install URL Prefix
```html
itms-services://?action=download-manifest&url=<plist link>
```

# Folder
**Provisioning Profiles folder path**
```ruby
~/Library/MobileDevice/Provisioning\ Profiles
```

# Xcode
### Packge Manager
* [Alcatraz](http://alcatraz.io) - The package manager for Xcode

### Plugin
* [KSImageNamed](http://ksuther.com/2013/01/22/ksimagenamed-xcode-autocomplete-for-imagenamed/) - Xcode autocomplete for imageNamed
* [VVDocumenter-Xcode](https://github.com/onevcat/VVDocumenter-Xcode) - Xcode plug-in which helps you write Javadoc style documents easier.
* [XToDo](https://github.com/trawor/XToDo) - Xcode plugin to collect and list the `TODO`,`FIXME`,`???`,`!!!!`.
* [CocoaPodUI](https://github.com/Galeas/CocoaPodUI) - Xcode plugin that implements CocoaPods GUI.

# Documentation
* [CocoaDocs](http://cocoadocs.org) - Hosted documentation for Mac / iOS libraries.