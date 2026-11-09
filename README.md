# Vinyl Inventory APP

Phone web app for vinyl skids. Open https://only-alpha.github.io/Vinyl-Inventory-APP/ on the phone.

- **Receiving**: scan each manufacturer's master label (qty + serial barcodes, 2P# read from the photo) and
  export the list; Skid Label Generator > Load Receiving prints one skid label per skid.
- **Inventory**: weekly count. Scan the skid label, enter yards (feet for bead / poly scrim), compare with last week,
  export for Finish Count on the PC.

This repo holds only the app. Material lists and counts are files kept in Google Drive (My Drive > Inventory Files);
none of that data is stored here. The source of truth is the counter/ folder in Only-Alpha/skid-label-generator.
