#iOS-Development

List of iOS Frameworks, Articles, E-Books and more.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](http://doctoc.herokuapp.com/)*

- [Articles](#articles)
- [CocoaPods Libraries](#cocoapods-libraries)
    - [Data Process](#data-process)
    - [Database](#database)
    - [Extension](#extension)
    - [Location](#location)
    - [Networking](#networking)
    - [Passbook](#passbook)
    - [ReactiveCocoa](#reactivecocoa)
    - [UI](#ui)
    - [My Podfile](#my-podfile)
- [Documentation](#documentation)
- [E-Book](#e-book)
- [Frameworks](#frameworks)
- [Websites](#websites)
- [Repository](#repository)
- [System](#system)
- [Swift](#swift)
- [Tools](#tools)
- [Xcode](#xcode)
    - [Packge Manager](#packge-manager)
    - [Plugin](#plugin)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Articles
* [The Right Way to Ask Users for iOS Permissions](https://medium.com/p/96fa4eb54f2c)
* [The New York Times Mobile Team’s Objective-C Style Guide](https://github.com/NYTimes/objective-c-style-guide#notifications)
* [How to Generate Beautiful Apple-Style Documentation in Xcode 5](http://ios-blog.co.uk/tutorials/how-to-generate-beautiful-apple-style-documentation-in-xcode-5/)
* [Taming Xcode by Jay Thrash](http://cocoaheads.tv/taming-xcode-by-jay-thrash/)
* [讓 Xcode 專案易於版本控制的方法](http://nelson.logdown.com/posts/2014/01/27/easy-version-control-mechanism-for-xcode-projects)
* [The official raywenderlich.com Objective-C style guide.](https://github.com/raywenderlich/objective-c-style-guide#language)
* [git-flow cheatsheet](http://danielkummer.github.io/git-flow-cheatsheet/) - This cheatsheet shows the basic usage and effect of git-flow operations
* [The official Swift style guide for raywenderlich.com.](https://github.com/raywenderlich/swift-style-guide)

# CocoaPods Libraries
### Data Process
* [NSDate-TKExtensions](https://github.com/mapedd/NSDate-TKExtensions.git) - Set of usefull categories for NSDate.

### Database
* [Realm](http://realm.io) - Realm is a modern data framework & database for iOS & OSX.
* [Realm-JSON](https://github.com/matthewcheok/Realm-JSON) - A concise Mantle-like way of working with Realm and JSON.
* [MagicalRecord](https://github.com/magicalpanda/MagicalRecord) - Super Awesome Easy Fetching for Core Data.

### Extension
* [onepassword-app-extension](https://github.com/AgileBits/onepassword-app-extension) - 1Password Extension for iOS Apps

### Location
* [MMPReactiveCoreLocation](https://github.com/mpurbo/MMPReactiveCoreLocation) - A reactive CoreLocation wrapper for use with ReactiveCocoa.

### Networking
* [AFNetworking](https://github.com/AFNetworking/AFNetworking.git) - A delightful iOS and OS X networking framework.

### Passbook
* [passbook](https://github.com/frozon/passbook) - Passbook gem let's you create pkpass for passbook iOS 6.

### ReactiveCocoa
* [ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa) - A framework for composing and transforming streams of values.
* [AFNetworking-RACExtensions](https://github.com/CodaFi/AFNetworking-RACExtensions.git) - A delightful extension to the AFNetworking classes for iOS and Mac OS X.

### UI
* [HexColors](https://github.com/mRs-/HexColors.git) - Easy HEX-Color and RGB-Color Handling for UIColor and NSColor as a drop in category. Former MLUIColorAdditions.
* [DZNEmptyDataSet](https://github.com/dzenbot/DZNEmptyDataSet) - A drop-in UITableView/UICollectionView superclass category for showing empty datasets whenever the view has no content to display.

### My Podfile
```ruby
# Database
pod 'Realm'

# Networking
pod 'AFNetworking'
pod 'AFNetworking-RACExtensions', :git => 'https://github.com/CodaFi/AFNetworking-RACExtensions.git', :tag => '0.1.5'

# ReactiveCocoa
pod 'ReactiveCocoa'

# UI
pod 'HexColors'
```

# Documentation
* [CocoaDocs](http://cocoadocs.org) - Hosted documentation for Mac / iOS libraries.

# E-Book
* [iOS Succinctly - FREE](http://ios-blog.co.uk/resources/ios-succinctly-free-e-book/)
* [iOS7 Day by Day](https://leanpub.com/ios7daybyday)

# Frameworks

# Websites
* [Swift Toolbox](http://www.swifttoolbox.io) - Swift toolbox is a community-supported catalog of iOS and OSX libraries written in the Swift Programming Language.

# Repository
* [iOS8-Sampler](https://github.com/shu223/iOS8-Sampler) - Code examples for the new functions of iOS 8.

# System
**Provisioning Profiles folder path**
```ruby
~/Library/MobileDevice/Provisioning\ Profiles
```

# Swift
* [An attempt to gather all that is in flux in Swift.](https://github.com/ksm/SwiftInFlux)
* [Alamofire](https://github.com/Alamofire/Alamofire) - Elegant Networking in Swift.
* [SwiftDate](https://github.com/haginile/SwiftDate) - A Smart Date/Calendar Library Written in Swift 
http://stockfuse.com

# Tools
* [Nomad](http://nomad-cli.com) - world-class command line utilities for iOS development
* [gitflow](https://github.com/nvie/gitflow) - Git extensions to provide high-level repository operations for Vincent Driessen's branching model.
* [Homebrew](http://brew.sh) - The missing package manager for OS X.
* [doctoc](https://github.com/thlorenz/doctoc) - Generates table of contents for markdown files inside local git repository. Links are compatible with anchors generated by github.

# Xcode
### Packge Manager
* [Alcatraz](http://alcatraz.io) - The package manager for Xcode

### Plugin
* [KSImageNamed](http://ksuther.com/2013/01/22/ksimagenamed-xcode-autocomplete-for-imagenamed/) - Xcode autocomplete for imageNamed
* [VVDocumenter-Xcode](https://github.com/onevcat/VVDocumenter-Xcode) - Xcode plug-in which helps you write Javadoc style documents easier.
* [XToDo](https://github.com/trawor/XToDo) - Xcode plugin to collect and list the `TODO`,`FIXME`,`???`,`!!!!`.
* [CocoaPodUI](https://github.com/Galeas/CocoaPodUI) - Xcode plugin that implements CocoaPods GUI.