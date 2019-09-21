# Xcode 11 c++ 6.0.9
Xcode11 c++6.0.9 
Xcode 11 支持使用lbstdc++

## Usage
根据调试方式不同，分别复制对应的Lib文件到下面的路径即可解决

###  真机 For Device
Put tbd copy to the path:

/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS.sdk/usr/lib/

### 模拟器 For Simulator
Put dylib copy to the path:

Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS.simruntime/Contents/Resources/RuntimeRoot/usr/lib

Put tdb copy to the path:

/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneSimulator.platform/Developer/SDKs/iPhoneSimulator.sdk/usr/lib/


