# [Sample plug-in: Related Record Count Plug-in]
## Purpose of the Sample Plug-in
This sample plug-in is available for educational purposes.  
Use this plug-in to understand how Kintone plug-ins work, and how they are structured.
A non-packaged version written with a single JavaScript file can be found here https://kintone.dev/en/tutorials/count-record-content/display-the-total-number-of-related-records/

## What the plug-in does
This plug-in displays the total number of records retrieved by a Related Records field within a Kintone App.
When a user sets up a Related Records field, the number of fetched Related Records will be displayed above the field in a Blank Space field.
The plug-in settings page allows the user to choose which Related Records field and Blank Space field will be used.

## Plug-in directory structure
This sample plug-in is created with the following directory structure.

src/  
├── html/  
│        └──── config.html  
├── css/  
│        ├──── 51-modern-default.css  
│        └──── config.css  
├── js/  
│        ├──── config.js  
│        └──── desktop.js  
├── image/  
│        └──── books.png  
└── manifest.json  

## How to use
To simply test out the plug-in on your Kintone domain, follow these steps:

1. Download the plug-in zip file  
Reference: https://github.com/kintone/SAMPLE-Related-records-count-plug-in/releases
2. Install the plug-in into your domain  
Reference: https://get.kintone.help/hc/en-us/articles/115001519707-Installing-Viewing-Plug-ins
3. Add the plug-in to a specific Kintone App  
Reference: https://get.kintone.help/hc/en-us/articles/115001511188-Adding-Plug-ins-to-an-App
4. Make sure that a Related Records field and a Blank Space field (with an Element ID set up) are placed in the form of your Kintone App. Access the plug-in settings, and set up the necessary settings. Save the settings, and update the App.
5. Click the + button on the Record List page to start adding a new record. After saving the record, if there are Related Records available, the number of fetched Related Records will be displayed in the Blank Space field.

## How to modify
1. Fork to your repo
2. Make changes to files under /src
3. Repackage the plug-in by:  
 i. Zipping the manifest.json file, css directory, html directory, image directory and js directory into one zip file.  
 ii. Drag and dropping the file into the [kintone plug-in packer](https://kintone.dev/en/plugins/plug-in-tool-guides/package-plug-in-files-using-plugin-packer/).

## Pull Request Policy
As this repo exists for educational purposes, we will most likely turn down pull requests that contain updates with new features.  
Please feel free to host plug-ins with new features on your own repository.
Bug fixes are happily accepted.
