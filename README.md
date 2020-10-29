# treeLUT

Most LabVIEW applications heavily rely on Clusters. However, these clusters get large and complex very quickly, and while the Bundle / Unbundle by Name VIs can conveniently hide unneeded elements in the block diagram, the same can not easily be done on the front panel. The `treeLUT` class provides a way to display nested Clusters in a Tree structure, and maps all elements to a look-up table (a `Variant` with hattributes) for easy access.
