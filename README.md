# Saikyo-iOS  

This repository is related to the development of **Saikyo** for iOS.

### Basic Overview of the Setup

* Languages: Swift 5.0 (iOS)
* Frameworks: See `Podfile`
* Database: Realm (For encrypted storage)
* Dependancy: CocoaPods
* Unit Testing: XCTest、Quick, Nimble
* Crash logging: Firebase Crashlytics
* CD: Undecided (Firebase App Distribution or Deploygate?)

### Branches

* develop -- for testing by only ML members
* release/* -- for testing by ML and Customer members (this contains new features, this must be branched from `develop`)
* hotfix/* -- for testing by ML and Customer members (this contains only urgent bugfix, this must be branched from `master`)
* master -- for production build.
* feature/* -- Topic branch, adding feature, bugfix, etc.

### Installation

* Clone this repository, or download the zip file.
* Navigate to the folder in Terminal
* Run `pod install`
* Open the workspace and run
