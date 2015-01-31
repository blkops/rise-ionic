# Rise Ionic

This repository holds the sources for the [Ionic-based][ionic] project for
Rise.

## Installation

 1. Install [Node][node] on your machine.
 2. Install [Ionic][ionic] and [Cordova][cordova] as well.

    `npm install -g cordova ionic`

 3. Install the platforms you'd want to target your development on. Note that
    iOS development is only available on OSX. Take a look at the [Getting
    Started with Ionic][gswi] page before continuing if you aren't familar with
    Ionic.

    `ionic platform add ios`

 4. Build & launch the project.

    `ionic build ios`
    `ionic emulate ios`

[node]: http://nodejs.org/download/
[ionic]: http://ionicframework.com/
[cordova]: http://cordova.apache.org/
[gswi]: http://ionicframework.com/getting-started/
[cordova_android]: http://cordova.apache.org/docs/en/3.3.0/guide_platforms_android_index.md.html#Android%20Platform%20Guide
[cordova_ios]: http://cordova.apache.org/docs/en/3.3.0/guide_platforms_ios_index.md.html#iOS%20Platform%20Guide
