# amd-gtfs
This repo houses GTFS feeds built from the [AMTS website](https://amts.co.in) and the [AJL website](https://ahmedabadbrts.org).
### gtfs.zip
This file stores data in the original format. If the AMTS / AJL website had two routes with the same name, destinations, and stop sequences they will be separate routes here. Good for research purposes and data processing.
### gtfs_compat.zip
This file stores data in the most compatible format. Routes are merged for simplicity, trips may have different stop sequences and directions. Ideal for Passenger Information Services like [transitrouter](https://transitrouter.pages.dev), [catenary maps](https://maps.catenarymaps.org), etc.

##### Note: All AJL IDs are prefixed with "BRTS_"
