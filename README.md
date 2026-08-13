# amd-gtfs
This repo houses GTFS feeds built from the [AMTS website](https://www.amts.co.in), [AJL website](https://ahmedabadbrts.org), and the [GTSL website](https://gscdlwebportal.gandhinagarsmartcity.in/).
### gtfs.zip
This file stores data in the original format. If the AMTS / AJL / GTSL website had two routes with the same name, destinations, and stop sequences they will be separate routes here. Good for research purposes and data processing.
### gtfs_compat.zip
This file stores data in the most compatible format. Routes are merged for simplicity, trips may have different stop sequences and directions. Ideal for Passenger Information Services like [transitrouter](https://transitrouter.pages.dev/#/ahmedabad/), [catenary maps](https://maps.catenarymaps.org), etc.

##### Note 1: All AJL IDs are prefixed with "BRTS_"
##### Note 2: GTSL trip times are sourced from Gandhinagar Municipal Corporation's website, they seem to potentially be obsolete.
