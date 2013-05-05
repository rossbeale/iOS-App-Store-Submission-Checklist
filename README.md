# iOS App Store Submission Checklist

A short checklist to run through **before** submitting an iPhone/iPad app to the App Store. Worth reading through at the beginning of projects, as well as just before submission.

*Note that this list is not fully encompassing - some new or rare issues may arise which are not present on this checklist. When in doubt, scour through [Apple's official guidelines](https://developer.apple.com/appstore/guidelines.html). If you find the answer you're looking for, try and help out others by contributing (submit a pull request!).*

## <a name='contents'>Contents</a>


  1. [Your app…](#app)
  1. [iPad specific](#ipad)
  1. [Submission package details](#submission)
  1. [Miscellaneous](#miscellaneous)
  1. [Copyright, trademark, ownership](#copyright)
  1. [Acknowledgments](#acknowledgments)

***
## <a name='app'>Your app…</a>

* Does not simulate a failure (e.g. crash or cracked screen)
* Remains responsive after long/excessive usage
* Does not hardcode any price information inside the app
* Does not make use of any private APIs in the SDK
* Does not make use of any undocumented features in the SDK
* Does not refer to hardware capabilities which don't exist on the users device
* Warns the user when there is no network connectivity, if it needs a connection
* Does not resemble (too closely) any native apps
* Does not replicate (too closely) the functionality of a native app
* Does not expire (stop working) after a certain time or number of runs
* Does not use any unapproved hardware accessories
* Does not contain contain racist material, prolonged graphic violence, graphic sexual content or nudity
* Does not "accidentally" contain such material, e.g. unrestricted web browsing, explicit lyrics, unfiltered collections of books
* Does not ridicule well-known public figures, past or present
* Does not contain a scripting interpreter, plugin or other runtime that can execute downloaded content
* Does not use continuous vibration
* Uses the relevant keyboard per input field (e.g. numbers for a phone number field)
* Deselects rows in table views after their selection causes another view to be displayed
* Restricts video streaming or other big downloads to WiFi connections only
* Makes clear to the user when private data will be sent to a server, and provides an opt-out
* Does not make covert or non-obvious use of the camera or microphone
* Uses Core Location (GPS) for a real user benefit, not just advertising or tracking (if applicable)
* Never crashes
* Conforms to Apple's Human Interface Guidelines
* App looks well designed and of high quality
* Native button icons are consistent with their native actions
* Activity spinners must not spin indefinitely
* Buttons trigger on touch-up
* Screen layout can handle the double-height status bar (e.g. during phone call)
* App state is saved when stopping the app and restored on next start
* Landscape mode, if supported, looks well designed (i.e. is not accidental and bad)

*** 
## <a name='ipad'>iPad specific</a>

* Your app should work in all four orientations, but if only portrait or landscape, must support both ways up
* Your app doesn't nest popovers, i.e. selecting something on a popover should not display another popover
* Your app doesn't show more than one popover at a time

***
## <a name='submission'>Submission</a>

* The name of your app (in the binary package) matches (or is abbreviated version of) the iTunes name
* Your iTunes description accurately describes the functionality of the app, i.e. it works as advertised
* Your iTunes description does not contain the price
* Your iTunes description (and the binary) do not include the names of any competing platforms (e.g. Android, Blackberry)
* Your iTunes description does not mention unreleased iOS version numbers
* Your iTunes keywords match the functionality of the app
* Your iTunes keywords do not contain the names of other apps
* If your app's price is over $100 or has in-app purchases over $100, it is rated 17+
* The screenshots do not include error states, including iAd errors
* The categories the app is in match its functionality
* Any easter eggs in the app are innocuous and are disclosed in the 'demo account' field
* Icons are provided for each of the sizes: 57, 72 (if on iPad), 114 and 512 pixels
* The different sizes of icon all contain the same artwork
* Version number (bundle version number) is >= 1.0
* The required-device-capabilities entry in the info.plist file match the requirements of the app
* Your app matches your claimed OS version compatibility
* NSZombieEnabled is set to NO
* App IP configured correctly (and signed) for
  * iCloud enabled/disabled, with correct entitlments if enabled
  * push notifications, with correct entitlements (for production) if enabled
  * In App purchasing enabled/disabled
  * Game Center enabled/disabled
* When updating
  * Your iTunes "What's New" description accurately matches the changes to your app
  * The updates to your app are real and detectable
  *  Version number is greater than the previous version number
  
***
## <a name='miscellaneous'>Miscellaneous</a>

* The app has a reasonably sized market, i.e. is not a tiny niche or for a private audience
* There are no greyed out buttons or features in your app to do with a future release
* Lite versions of apps must not be unusably restricted; they have to "work" as is
* Lite versions of apps cannot be time limited
* Lite versions must not display the price of the full version
* Webpages loaded by the app, that are part of the app itself, are online and working
* Any associated email addresses exist and are working
* All (paid) app upgrades and other transactions use the App Store
* The app is not a simple browser window onto a website
* The app conforms to any regulatory requirements, e.g. if the app is medical in nature, or contains contests with prizes
* If relevant, official rules for sweepstakes and contests are presented in the app
* If relevant, the app makes it clear that Apple is not a sponsor or involved with any sweepstakes, contests or their prizes
* If you use encryption, you have registered with BIS and can provide documentation
* If your app requires signing in, you have provided test account
* If your app uses old style MapKit, it does not hide or obscure the Google logo
* If using the camera, your app doesn't disable the shutter sound
* Any references to Apple's products or apps are spelled correctly

***
## <a name='copyright'>Copyright, trademark, ownership</a>

* You can prove you own (or have permission to use) all the code in your app
* You can prove you own (or have permission to use) all the artwork in your app
* You can prove you have permission to use any brand names, names of public figures or other trademarked material
  * e.g. Images and icons are not framed with a "polaroid" style (thicker at the bottom) border
  * e.g. Images and icons do not include iPhones or other Apple products
* You can prove you own (or have permission to use) any videos, music or lyrics in your app
    
***
## <a name='acknowledgments'>Acknowledgments</a>


* Initially crafted by TestPad, over [here](https://ontestpad.com/library/201/ios-app-store-submission-checklist).
* [Ross Beale](http://www.rossbeale.com).

Want to improve the list? Submit a `Pull Request`!