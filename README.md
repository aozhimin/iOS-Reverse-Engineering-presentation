# iOS-Reverse-Engineering-presentation

## Overview
iOS-Reverse-Engineering-presentation introduce the knowledge and tool chain of reverse engineering of iOS, which covering the basic use of reverse engineering of iOS.

![OverView](https://github.com/aozhimin/iOS-Reverse-Engineering-presentation/blob/master/images/overview.jpeg)

## Usage
clone the repo and open the index.html to show the slides or click github io link.

## Resources
* [class-dump](https://github.com/nygard/class-dump)
* [Theos](https://github.com/theos/theos)
* [iOSOpenDev](https://github.com/kokoabim/iOSOpenDev)
* [IDA](https://www.hex-rays.com/products/ida/)
* [Hopper](https://www.hopperapp.com/)
* [MachOView](https://github.com/gdbinit/MachOView)
* [dumpdecrypted](https://github.com/stefanesser/dumpdecrypted)
* [Clutch](https://github.com/KJCracks/Clutch)
* [cycript](http://www.cycript.org/)
* [LLDB commands](https://objccn.io/issue-19-2/)
* [chisel](https://github.com/facebook/chisel)
* [iosre](http://iosre.com/)

## Workaround
when you start iOS Reverse Engineering, you should install many tools, You may encounter a variety of problems. Here is a list of possible workarounds.

* [The solution to the failure of the iOSOpenDev installation
](https://www.ianisme.com/ios/2319.html)
* [The solution to the failure of make package](https://blog.sunnyyoung.net/post/ni-xiang/2017-01-11-theosan-zhuang-yu-pei-zhi)

> when you execute `make package` command to package, you may encounter a failure situation, wrong prompt is "dpkg-deb: warning: deprecated compression type 'lzma'; use xz instead'", you should change value of `_THEOS_PLATFORM_DPKG_DEB_COMPRESSION` to xz

## Author
Alex Ao, aozhimin0811@gmail.com

## License

iOS-Reverse-Engineering-presentation is released under the MIT license. See LICENSE for details.

