phonegap-whitelist-test
=======================

Test XHR from remote resource to whitelisted domain within Phonegap on iOS.

## Test XHR from file: location ##
1. Install `ios-sim`: `brew install ios-sim`
2. Checkout the load-locally directory.
3. Run `./cordova/build; ./cordova/run`
4. See placekittens.

## Test XHR from remote location ##
1. checkout the load-remotely directory.
2. Run `./cordova/build; ./cordova/run`
3. Cross-domain request restrictions prevent XHR; no placekittens.
