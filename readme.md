# The Gig Is Up

#### *A software engineering project from the University of Leeds.*

The Gig Is Up is a gig booking system which allows users to view upcoming events around the UK. It has the following features:

- View a list of artists, events and previous bookings.
- View a seating plan.
- Sign up, change username, change email address, change password.
- Make a booking with a card.

**Note: This app is a purely a mockup and no actual purchasing happens. Do not use actual card details when purchasing a ticket.**


### Download from Google Play

<a href="https://play.google.com/store/apps/details?id=com.dolphin.thegigisup&utm_source=global_co&utm_medium=prtnr&utm_content=Mar2515&utm_campaign=PartBadge&pcampaignid=MKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1"><img alt="Get it on Google Play" src="https://play.google.com/intl/en_us/badges/images/generic/en-play-badge.png" width="200px" /></a>

--------------------------------------------------------------------------------

### Installation instructions

#### Command Line:

Note: If you are on Windows you may have to substitute `gradle` with `gradlew` below.

    $ git clone https://github.com/the-gig-is-up/android.git
    $ gradle build
    $ gradle installDebug


#### Installation via IntelliJ:

 - Clone the repo `git clone https://github.com/the-gig-is-up/android.git`.
 - Open the newly created `android/build.gradle` using IntelliJ's `Open`.
 - Ensure that you select `local gradle distribution`.
 - Once inside the project, allow gradle to sync.
 - You can now setup `adb` to install the app.


### Testing

 - Testing in the app has only been tested in IntelliJ.
 - It requires the phone to be plugged in, with USB debugging enabled.


We have a custom XML file to handle testing. The file can be found on the wiki. Add the file to the folder `.idea/runConfigurations`.

Once this file has been added, a new build configuration will be added called
"AppTester". This requires an Android device to be plugged in and unlocked, with USB debugging:

- Click run, and the tests will run.
- If you wish to see all tests, ensure that `Hide passed tests` is not clicked in the Run tab of IntelliJ.

--------------------------------------------------------------------------------

### FAQ

**Q:** This isn't working in my IDE!
**A:** This was developed in IntelliJ IDEA, but should work
   with Android Studio and Eclipse, but this has not been tested, and may
   require more work.

**Q:** What versions of Android has this been tested on?
**A:** The development team has tried this on 4.4, 5.0, and 5.1. Lower versions
   should also work.


---------

Android, Google Play and the Google Play logo are trademarks of Google Inc.
