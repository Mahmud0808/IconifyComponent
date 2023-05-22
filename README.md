# Iconify Component

## Pre-made overlay's source.

### How to build these Runtime Resource Overlays?

#### There are actually 3 ways to build them into usable overlays.

- AAPT Tool:

    - Create and put AndroidManifest.xml in every folder.
    - Run AAPT command on your terminal to build APK.
    - Don't forget to ZipAlign and Sign the APK later.

- Substratum Theme Template:

    - Put all the folders in your Substratum Theme's assets/overlays folder.
    - Rename the folders according to Substratum Theme Template's documentation.
    - Use Substratum or Substratum Lite to build and apply the overlays.

- Iconify:

    - Put all the folders in Iconify's assets/Overlays folder.
    - Clear data of Iconify.
    - Run Iconify and the APKs will be built automatically.
