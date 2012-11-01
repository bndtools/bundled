bundled
=======

A repository for turning existing JARs into bundles, providing proper metadata.

One of the drawbacks of using OSGi is that not all JARs are componentized. In practice, 
this has meant that (too) many companies spent effort on providing OSGi metadata. This
redundancy does not only mean a waste of man hours, it also causes inconsistency since
not everybody makes the same choices.

The intention of this repository is to collect all recipes (bnd files) in one place
and build the resulting bundles from it.

