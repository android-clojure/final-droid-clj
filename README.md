# SecondApp

This is a "sandbox" application based on the Leiningen droid template. 

## Usage

To build and push an APK to an attached device use `lein droid doall` at the CL, or create a Leiningen
Run Configuration in Android Studio with the arguments `droid doall`

## Notes
The master repository for the Leiningen template was broken on Leiningen 2.8.1 as the package for
a critical dependency had changed. I think the last update to the plugin was Oct 2016, which doesn't
exactly give one the warm fuzzies.

## License

Copyright © 2018 Ian Coleman

Distributed under the Eclipse Public License, the same as Clojure.
