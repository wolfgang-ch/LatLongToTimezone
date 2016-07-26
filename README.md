# LatLongToTimezone
Lat/long to timezone mapper in Java and Swift. Does not require web services or data files.

99% of people using this project just need the one file:

(Java)
https://github.com/drtimcooper/LatLongToTimezone/blob/master/src/main/java/com/skedgo/converter/TimezoneMapper.java

(Swift)
https://github.com/drtimcooper/LatLongToTimezone/blob/master/Classes/TimezoneMapper.swift

(CSharp)
https://github.com/drtimcooper/LatLongToTimezone/blob/master/Output/Toolbox.TimeAndDate.TimezoneMapper.cs

# Usage

On iOS, the code is available as a CocoaPod.  Just add this to your Podspec:

```
pod 'LatLongToTimezone'
```

Then in your code, you can do

```Swift
import LatLongToTimezone

let location = CLLocationCoordinate2D(latitude: 34, longitude: -122)
let timeZone: NSTimeZone = TimezoneMapper.latLngToTimezone(location)

```
