# Scripts

This directory contains various scripts for generating supporting libraries (e.g. CBECC-Com constructions)

## CBECC-Com

To recreate the constructions for CBECC-Com:

* Checkout CBECC-Com's "source code" from https://code.google.com/p/cbecc/ into a directory named cbecc at the same level as the OpenStudio Standards checkout
* `cd scripts` -- make sure that you are in the scripts folder
* `ruby import_cbecc_materials.rb`
* Manually copy/paste the materials.csv into the OpenStudio_Standards.xlsx file.
* Run `rake build:standards` from the root of this repository
* Refer to the [OpenStudio-CBECC Library Generator Readme](https://github.com/NREL/openstudio-cbecc/blob/master/LibraryGenerators/README.md) to complete the CBECC-Com library import

