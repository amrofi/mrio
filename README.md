Work with MRIO data
===================

This R-package provides various calculation methods for
environmentally-extended multi-regional input–output (EE-MRIO) analysis.
It includes different characterization factors.

-   currently supports Exiobase3 and Eora
-   calculate:
    -   **b**iodiversity **l**oss `"bl"` (currently only for Exiobase)
    -   **b**lue **w**ater consumption `"bw"`
    -   **c**limate **c**hange impacts `"cc"`
    -   **en**ergy demand `"en"`
    -   **l**and **u**se `"lu"`
    -   **m**aterial **f**ootprint `"mf"`
    -   **w**ater **s**tress `"ws"` (currently only for Exiobase)
-   calculate:
    -   **p**roduction to **d**emand matrix `"pd"`
    -   **p**roduction to target **d**emand matrix `"no-double-pt"`
    -   **t**arget to final **s**upply matrix `"no-double-ts"`
    -   **t**arget to final **d**emand matrix `"no-double-td"`
    -   **p**roduction to final **d**emand matrix `"no-double-pd"`
-   create country-dyads

First Steps
-----------

Before you begin, set your working directory to the path where you store
your Eora and Exiobase files:

`setwd("C:/Data/Exiobase)`

Plan
----

-   add WIOD
-   add bl and ws for Eora
-   automated download of the data sets
