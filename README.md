# FVTT-DD-Importer
Allows Importing Dungeondraft map files into FoundryVTT

**Version 0.10**

Manifest: `https://raw.githubusercontent.com/timothy-s-dev/FVTT-DD-Import/master/module.json`


## Usage Instructions

1. Export your map with the Universal VTT option in Dungeondraft.
2. Go to the scene tab in FVTT, click the Dungeondraft Import button.
3. Fill in the scene name, a path to where the image is to be saved, and the fidelity/offset options.  
  a. **Fidelity**: How many cave walls are used. Far left - less walls, better performance, Far right - more walls, worse performance  
  b. **Offset**: How much to nudge the walls away from the edge.

  If you don't use S3, make sure the storage type is set to User Data and ignore the S3 fields.
