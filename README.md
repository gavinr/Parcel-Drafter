# Parcel-Drafter

Parcel Drafter is a Web AppBuilder (Developer Edition) custom widget designed to create and edit parcels.  This widget can be used create an application to supplement your on-premise parcel data management workflow, or used as a lightweight, standalone application.

[Try the Parcel Drafter application](http://links.esri.com/localgovernment/tryit/ParcelDrafter/)

[![Image of Parcel Drafter application](ParcelDrafter.png "Parcel Drafter application")](http://links.esri.com/localgovernment/tryit/ParcelDrafter/)

## Features
* Coordinate Geometry (COGO)
* Recorded document tracking/routing
* Focused editing workflow

## Requirements

**Start now by downloading and installing [Web AppBuilder (Developer Edition)](https://developers.arcgis.com/web-appbuilder/) and adding the custom widget**

You can start using the Parcel Drafter widget now by adding the "Parcel Drafter" folder to 2D widget folder (\WebAppBuilderForArcGIS\client\stemapp\widgets) in Web AppBuilder (Developer Edition) then restarting Web AppBuilder. For additional information use the following steps to deploy a custom widget [Web AppBuilder (Developer Edition) depoly a custom widget](https://developers.arcgis.com/web-appbuilder/guide/deploy-custom-widget-and-theme.htm)

**Start now using your own services, you'll want to publish a Parcel Drafter service when developing. The help below will walk you through this process**

For more information on requirements and publication steps, see [Parcel Drafter ](http://links.esri.com/localgovernment/help/ParcelDrafter/) help.

### Experience

* Using Web AppBuilder (Developer Edition)
* Publishing aervices and authoring maps using ArcGIS Online

### Software
* ArcGIS Online subscription
* Web AppBuilder (Developer Edition) 


## Instructions



### Deploying

1. To deploy this application, download the template from Portal/ArcGIS Online and unzip it.
2. Copy the unzipped folder containing the web app template files, such as index.html, to your web server. You can rename the folder to change the URL through which users will access the application. By default the URL to the app will be `http://<Your Web Server>/<app folder name>/index.html`
3. Change the sharing host, found in defaults.js inside the config folder for the application, to the sharing URL for ArcGIS Online or Portal. For ArcGIS Online users, keep the default value of www.arcgis.com or specify the name of your organization.
  - ArcGIS Online Example:  `"sharinghost": location.protocol + "//" + “<your organization name>.maps.arcgis.com`
  - Portal Example where `arcgis` is the name of the Web Adaptor: `"sharinghost": location.protocol + "//" + "webadaptor.domain.com/arcgis"`
4. If you are using Portal or a local install of the ArcGIS API for JavaScript, change all references to the ArcGIS API for JavaScript in index.html to refer to your local copy of the API. Search for the references containing `"//jsdev.arcgis.com/3.16"` and replace this portion of the reference with the url to your local install.
  - For example: `"//webadaptor.domain.com/arcgis/jsapi/jsapi"` where `arcgis` is the name of your Web Adaptor.
5. Copy a group ID from Portal/ArcGIS Online and replace the default group ID in the application’s default.js file. You can now run the application on your web server or configure the application further.

> **Note:** If your application edits features in a feature service, contains secure services or web maps that aren't shared publicly, or generate requests that exceed 200 characters, you may need to set up and use a proxy page. Common situations where you may exceed the URL length are using complex polygons as input to a task or specifying a spatial reference using well-known text (WKT). For details on installing and configuring a proxy page see [Using the proxy](https://developers.arcgis.com/javascript/jshelp/ags_proxy.html). If you do not have an Internet connection, you will need to access and deploy the ArcGIS API for JavaScript documentation from [developers.arcgis.com](https://developers.arcgis.com/).

### Browser Compatibility
* The application is optimized for display on desktops and tablet devices using the following browsers:
Microsoft Internet Explorer 10, 11
Mozilla Firefox
Google Chrome
Apple Safari
Microsoft Edge

## Resources

Additional [information and sample data](http://links.esri.com/localgovernment/download/ParcelDrafter/) are available for the application.

Learn more about Esri's [ArcGIS for Local Government maps and apps](http://solutions.arcgis.com/local-government/).

Show me a list of other [Local Government GitHub repositories](http://esri.github.io/#Local-Government).

[Esri's ArcGIS Online Help](http://doc.arcgis.com/en/arcgis-online/) site describes how to create web maps and web map applications in the ArcGIS Online ecosystem.

## Issues

Find a bug or want to request a new feature?  Please let us know by submitting an issue.

## Contributing

Esri welcomes contributions from anyone and everyone. 
Please see our [guidelines for contributing](https://github.com/esri/contributing).

## Licensing

Copyright 2016 Esri

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

A copy of the license is available in the repository's
[LICENSE.txt](LICENSE.txt) file.

[](Esri Tags: ArcGISSolutions Local-Government Local Government Parcel Drafter Deed Drafter)
[](Esri Language: JavaScript)

