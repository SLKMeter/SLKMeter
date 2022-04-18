[![SLKMeterIcon_192x192_rounded](https://user-images.githubusercontent.com/103928477/163871994-09620e4e-c122-40eb-a440-44f9771768af.png)](https://slkmeter.github.io/SLKMeter-Android/)
# SLKMeter for Android
Published binary for SLKMeter v1.2 (final release) for Android

**SLKMeter** is provided by **Fulton Hogan Industries** for those who might find it useful. It is not open source, and the code is not available in this repository, although it is free to use

**SLKMeter** provides real time referencing using the device GPS. It is designed to locate the user along a linear referenced network such as road, rail or pipeline, where mile (or kilometre) posts would be familiar. It is a modern trip meter and provides automatic correction for network 'rubber banding' between referenced and measured distance.
By default, **SLKMeter** is used on the state and local government road networks of Western Australia. It has also been trialled with the Australian state networks of Victoria, South Australia and Queensland, as well as internal road networks of mining tenements, although the network definitions and publicly available data from those states are less suitable and is considered largely experimental. The use of other networks is partly supported by arrangement via app help request or by email.

## Download
**SLKMeter** is no longer available from the Google app store, so the final release is now hosted here and can be downloaded from the link below. It should be downloaded direct to the device.
[SLKMeter v1.2](https://github.com/SLKMeter/SLKMeter-Android/releases/download/v1.2/com.fultonhogan.slkmeter_1.2.apk)  
**SLKMeter** for IOS is available from [![image](https://user-images.githubusercontent.com/30642712/163707327-d868917b-a948-40ba-ad1d-ae134104b6db.png)](https://itunes.apple.com/app/id1024397024)


## Installation
After download there is usually a prompt to install files of this type, along with security warnings - install at your own risk. If that doesn't occur, look for the file in your downloads folder (com.fultonhogan.slkmeter_1.2.apk) and tap it. You may also be prompted to allow permission to install from Unknown Sources, if not see below.
**Notes:**  
- To install application binaries directly on Android devices, or sideloading as it is commonly known, the Android Security settings need to be set to allow Unknown Sources beforehand. The setting is buried in Apps and Notifications in recent Android versions, but may be in Privacy/Security in earlier versions. Googling install android apk might help.
- This is the same app and version that was available in the Google app store, but installation of this release which is unverified by Google is entirely at the user's risk.

## Usage
### Initial use
- Users are required to log in to or create an **SLKMeter** account.
- During setup the Login screen is displayed. If the user has an existing account, they should log in to it, if not, the Register button is below but may be obscured by the keyboard on some devices. Scroll down.
- If registration fails, it may be because there is a long forgotten existing account. You can check by using a password reset.
- **Note:** There is a bug with some keyboards which add spaces after dots when typing the email address. Please check carefully. Also note that an accepted predictive text suggestion may have been previously mistyped if the login is rejected.
- After login there is a prompt to download data. This is the latest (Western Australian by default) road network data, and this is required for **SLKMeter** to operate. It also requires permission to use the Location/High accuracy/GPS. Ensure to set this permission during installation, or afterwards in the settings. 
- If **SLKMeter** reports no GPS fix, this is a problem with the device settings or hardware.
### Referencing
![image](https://user-images.githubusercontent.com/30642712/163664851-43d71c2c-51d0-4729-a2f4-b713b238510d.png)
- **SLKMeter** continually reports the SLK (Straight Line Kilometre) location of the device, providing the device is within a reasonable distance (50m) of a gazetted Western Australian road 
- The street name field refers to the Route Name, which may differ from the posted street name.
- SLK + and - signs indicate the direction of travel. These may be inconsistent when stationary.
### Coordinates
![image](https://user-images.githubusercontent.com/30642712/163664776-c17171d9-b962-4032-872d-3785c5053a55.png)
- There is a known bug where Eastings and Northings are reversed.
- The trip meter function is a convenience only and should not be relied on, especially for long periods as backgrounding may cause the GPS to pause.
### App info
![image](https://user-images.githubusercontent.com/30642712/163664866-b654defd-031a-4b68-bd63-c03b55d1388e.png)
- The app info page provides information about the app, current data and the logged in account.
- Automatic data updates are not supported, although notifications of available updates may be provided.
- The database name can be used to check the data currency. The name has the 4-digit format YYMM appended to it.
- A data update can be triggered by the Check for Update button. Whilst this process will update the data, a known bug prevents the database name from updating. This will only occur after logging out then back in, which triggers an update anyway.
### Getting help
- Help is available, but not 24/7
- Help can be requested from the login screen or by email at [Support](mailto:slkmeteradmin@slkmeter.com.au)
- Please provide some details of your issue, or you may just get a password reset offer.
- If you're having trouble logging in and are sure your credentials are correct, you can try logging in to your account at the [SLKMeter website](https://www.slkmeter.com.au)

## Warning
**SLKMeter** prevents the device from sleeping and keeps the screen active, while using the GPS. All of this will necessarily take is toll on the device battery. Extended use of **SLKMeter** is best with the device on charge.

## Contact
[Support](mailto:slkmeteradmin@slkmeter.com.au)




## Licence
- **SLKMeter** remains the property of **Fulton Hogan Industries**.
- The use of **SLKMeter** is entirely optional.
- The use of **SLKMeter** requires registering an **SLKMeter** account and is free to use.
- **SLKMeter** is provided as is with no stated or implied warranty
- **Fulton Hogan** reserves the right to withdraw this service as circumstances dictate
