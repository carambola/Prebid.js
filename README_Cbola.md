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

When running the build-modules a bundle with specific modules (adaptors) are being included.

The adaptors are selected according to the `modules.json` file - which should be aligned 
with the HB providers.
