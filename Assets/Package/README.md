# Revenue Cat for Unity (unofficial)

Revenue Cat Integration for Unity

This repository redistributes RevenueCat Purchases package through UPM on 
the same license terms as the original one.

RevenueCat don't have support UPM offially, and while this,
this repository it support this method of install.

As soon as an official solution appears, this repo will be archived!

## How to install

At package.json, add these 2 lines of code:
```json
"com.gameworkstore.revenuecat": "https://github.com/GameWorkstore/revenuecat.git#4.3.0",
"com.google.external-dependency-manager":"https://github.com/GameWorkstore/com.google.external-dependency-manager.git#1.2.172",
```

And wait for unity to download and compile the package.

or update package for a newer version, update end of line from 0.2.1 to any released version on Releases.
