# com.nortal.cordova-plugin-passgetter

This plugin provides support for showing Passbook passs to your users and allows them to add it to their native Wallet (regardless of how you create your passes, whether you do it on your own or using any third-party services like [PassSlot](http://www.PassSlot.com))

**NOTE**: This plugin does not allow you to create Passbook passes.

## Installation

    cordova plugin add cordova-plugin-passgetter
    

## Supported Platforms


- iOS

## Example


    Passbook.downloadPass('https://d.pslot.io/cQY2f', token, function (pass, added) {
        console.log(pass, added);
    }, function (error) {
        console.error(error);
    });
