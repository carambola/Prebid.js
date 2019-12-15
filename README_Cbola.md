# Carambola README

## Providers

Carambola's current HB providers are:

* 152 Media
* 33Across
* Appnexus
* Conversant
* DistrictDMX
* EMX Digital
* Free Star (Index Exchange)
* Oath Inc. (AOL)
* OpenX 
* Pubmatic
* Rhythmone
* Rubicon
* Smart
* Sovrn
* E-Planning

## Build

The build process is performed by running the following command:

`npm run build:modules`

After running the `build:modules` command a bundle with the specific modules (adaptors) 
will be created.

The adaptors are selected according to the `modules.json` file - which should be aligned 
with the HB providers.

## Adding Providers

The first step is to figure out what is the bidder code of the provider.
For example: `E-Planning` is `eplanning`.

See the [Bidder Docs](http://prebid.org/dev-docs/bidders.html)

The second step is to find the adaptor for the provider in the `modules` folder.

If there is no such provider, it may mean that it is aliased.
To verify this, search for the bidder code in the `modules` folder.
