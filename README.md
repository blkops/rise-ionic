# Rise Ionic

This repository holds the sources for the [Ionic-based][ionic] project for
Rise. For the server side communications, check out [**blkops/rise-api**][api].

## Installation

 1. Install [Node][node] on your machine.
 2. Install [Ionic][ionic] and [Cordova][cordova] as well.

    `npm install -g cordova ionic`

    Then install the project dependencies.

    `npm install`

 3. Install the platforms you'd want to target your development on. Note that
    iOS development is only available on OSX. Take a look at the [**Getting
    Started with Ionic**][gswi] page before continuing if you aren't familar with
    Ionic. Also for Android development, ensure that you've installed the
    [**Android SDK**][adk]

    $ ionic platform add ios      # Only on OS/X
    $ ionic platform add android

 4. Build & launch the project.

    ```
    # For iOS
    $ ionic build ios
    $ ionic emulate ios

    # For Android
    $ ionic build android
    $ ionic emulate android
    ```

[api]: https://github.com/blkops/rise-api
[node]: http://nodejs.org/download/
[ionic]: http://ionicframework.com/
[cordova]: http://cordova.apache.org/
[adk]: http://developer.android.com/sdk/index.html#Other
[gswi]: http://ionicframework.com/getting-started/
[cordova_android]: http://cordova.apache.org/docs/en/3.3.0/guide_platforms_android_index.md.html#Android%20Platform%20Guide
[cordova_ios]: http://cordova.apache.org/docs/en/3.3.0/guide_platforms_ios_index.md.html#iOS%20Platform%20Guide
