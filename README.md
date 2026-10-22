# web2apk

Turns a website link or your own HTML files into an installable Android APK, built by GitHub Actions.

## Make an APK from a link
1. Repo -> **Actions** -> **Build APK** -> **Run workflow**
2. Enter app name, the website link, and a package id (e.g. `com.me.mysite`)
3. When the run is green, open it and download the **app-apk** artifact (a zip with the .apk inside)

## Make an APK from HTML files
1. Put your files in the `www/` folder (the entry page must be `www/index.html`)
2. Run the workflow with the **url** field left empty

## Install
Open the .apk on your phone and allow "install unknown apps" for your browser/files app when asked.
It is a debug-signed build, which installs fine for personal use.
