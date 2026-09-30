# Wildframe

A browser-based photo collage editor with two geometric animal head templates.

## Use the app

Choose Cat or Lynx, tap a numbered section, and select a photo. Move, zoom, or rotate each photo independently. Small lynx facial details remain black.

Download the finished collage as a one-page A4 PDF at 300 dpi. Print on A4 at **Actual size / 100%**. Empty sections print white; section numbers and editor controls do not appear in the PDF.

The responsive interface supports phones and computers. On phones, shape selection and crop controls are below the canvas. Pinch to zoom an added photo.

## Privacy and saving

Photos are processed on the device and are never uploaded by the app. Progress is stored in this browser using IndexedDB when available. Clearing browser data, private browsing, or changing devices may make saved work unavailable; download the finished PDF.

Sharing the app link does not share your photos or draft. Every visitor creates their own collage.

## GitHub Pages

This app is a single self-contained `index.html` file. There are no dependencies, API keys, or server components.

In repository **Settings → Pages**, select **Deploy from a branch**, then **main** and **/ (root)**. Save. GitHub will show the live website link after deployment.

Open that website link on phones; the repository page displays the source files.

## Local use

Download `index.html` and open it in a browser. Some mobile operating systems block downloaded HTML applications, so use the website link on phones.

## Templates

The animal templates were traced from reference images supplied for this project. No ownership or license to those reference designs is asserted by this repository.
