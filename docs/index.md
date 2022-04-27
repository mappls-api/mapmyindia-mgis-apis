[<img src="https://www.mapmyindia.com/api/img/mapmyindia-api.png" height="40"/>](https://www.mapmyindia.com/api)

# MapmyIndia mGIS APIs

## Introduction
Using these APIs developers can fully leverage and embed the power of GeoSpatial Analytics, GIS and location intelligence and AI. These APIs allow a developer to integrate into their own application the power and full set of functionalities of the mGIS product and platform.

## API Features

mGIS APIs are grouped under various categories providing wide range of functionalities
which can be leveraged by enterprise and consumer

- [Search & Navigation APIs](#search-and-navigation-apis)
- [Data Operations APIs](#data-operations-apis)
- [Layer Styling APIs](#layer-styling-apis)
- [Dataset Query & Validation APIs](#dataset-query-and-validation-apis)
- [Layer Visualization & Info APIs](#layer-visualization-and-info-apis)
- [Satellite Image Segmentation API](#satellite-image-segmentation-api)
- [Raster Catalogue APIs](#raster-catalogue-api)

## How mGIS APIs Enhance Value of any Solution
mGIS can serve different types of customers on the basis of the type of analytics
OR on the basis of the type of datasets they possess. E.g. a user who has a non spatial address dataset wants to upload on mGIS and perform geospatial visualization and queries.

<img src="./images/userstiory_section1.gif?raw=true" width="800px" style="margin-left:auto;margin-right:auto"/>

### [See Video Demo](https://www.mapmyindia.com/api/mgis-api/images/mgis/how-mgis-apis-e-value-of-any-solution_1.mp4)

### For this you will perform below steps:
- Use ‘generate batch geocode layer’ to get geospatial references of your dataset
- Use SAT API to save the resultant as a new layer or append into existing layer (above steps will add layer with basic style)
- Use Styling API in case you need to do visualisation based analytics
- Use Layer Visualisation API to get WMS image and feature info of a feature. Using this API you can also get the legend of the layer
- Use Dataset Query APIs to perform basic and cross join analytics on your dataset, resultant of which can be further saved.

<br>

## Search And Navigation APIs
Search and Navigation APIs group consist of APIs which can be used to perform batch operations.

These APIs can take input in several form factors:
```
.csv | .xlsx | xls | XLSX | XLS | xlt | XLT | xlsm | XLSM | xltx | XLTX
```

<img src="./images/BatchOperatoions.gif?raw=true" width="800px" style="margin-left:auto;margin-right:auto"/>

### Documentation
[Contact API Support](mailto:apisupport@mapmyindia.com)

### [See Video Demo](https://www.mapmyindia.com/api/mgis-api/images/mgis/search-and-navigation-apis-mgis.mp4)

### Generate Batch Geocode Layer
This API is useful if the user has a list of addresses and wants to have them georeferenced for visualization and analytics.
### Generate Batch Rev-Geocode Layer
If the user has a list of latitude and longitude values and wishes to categorize them based on belonging to residential/commercial areas, this API can be used.
### Generate Batch Routing Layer
Generally, when a user wishes to see multiple routes for multiple route points and wants to align them visually on the basis of travel time/distance to make some decision, this API is used to generate said travel graphs.

<br>

## Data Operations APIs
This group of APIs are used for adding the datasets in different formats to the mGIS engine

These APIs support below datasets:
```
GEOJSON | KML | CSV | XLSX | XLS | SHP(ZIP) | XLSM | XLT | XLTX
```

<img src="./images/getdataset_section3.gif?raw=true" width="800px" style="margin-left:auto;margin-right:auto"/>

### [See Video Demo](https://www.mapmyindia.com/api/mgis-api/images/mgis/data-operation.mp4)

### SAT (Save, Append and Truncate) API
This API is used to save user dataset with multiple saving options like append, truncate etc. on mGIS cloud with basic visualisation style.

#### Documentation
[Click here](https://mapmyindia.github.io/mapmyindia-mgis-apis/mgis-apis.html?urls.primaryName=Data%20Operations%20APIs%20%3E%20SAT%20APIs)

### Describe Dataset API
Describe Dataset API provides all attribute names along with the data type of a dataset.

#### Documentation
[Click here](https://mapmyindia.github.io/mapmyindia-mgis-apis/mgis-apis.html?urls.primaryName=Data%20Operations%20APIs%20%3E%20Describe%20Dataset%20API)

### Get Layer List API
This API lists down all the datasets that exist on an mGIS user’s cloud along with the geometry type of each dataset.

#### Documentation
[Click here](https://mapmyindia.github.io/mapmyindia-mgis-apis/mgis-apis.html?urls.primaryName=Data%20Operations%20APIs%20%3E%20Get%20Layer%20List%20and%20Legends%20APIs)

### Get Geometry Type API
This API returns the geometry type of a single dataset (Line/Point /Polygon/Multi Geometry).

#### Documentation
[Click here](https://mapmyindia.github.io/mapmyindia-mgis-apis/mgis-apis.html?urls.primaryName=Data%20Operations%20APIs%20%3E%20Get%20Geometry%20Type%20API)

### Get Dataset API
This API reads a dataset with options like read entire dataset, read only specific attributes of a dataset etc.

#### Documentation
[Click here](https://mapmyindia.github.io/mapmyindia-mgis-apis/mgis-apis.html?urls.primaryName=Data%20Operations%20APIs%20%3E%20Get%20Dataset%20API)

<br>

## Layer Styling APIs
Layer Styling API is used to update and add new styles to existing datasets.

<img src="./images/07_Style.gif?raw=true" width="800px" style="margin-left:auto;margin-right:auto"/>

#### Documentation
[Contact API Support](mailto:apisupport@mapmyindia.com)

### [See Video Demo](https://www.mapmyindia.com/api/mgis-api/images/mgis/layer-styling-apis.mp4)

These layer styles are listed below:
- Basic Style
- Category Based Style
- Bubble Style
- Cluster Style
- Gradient Style
- Heatmap Style
- Pie Chart Style
- Bar Chart Style
- D3bubble style
- Style with label

<br>

## Dataset Query And Validation APIs
This group of APIs are used to perform different data analytics and save results as a new dataset.

<img src="./images/04_QueryBuilder.gif?raw=true" width="800px" style="margin-left:auto;margin-right:auto"/>

#### Documentation
[Click here](https://mapmyindia.github.io/mapmyindia-mgis-apis/mgis-apis.html?urls.primaryName=Dataset%20Query%20And%20Validation%20APIs)

### [See Video Demo](https://www.mapmyindia.com/api/mgis-api/images/mgis/dataset-query-and-validation-apis.mp4)

User can perform below operations on dataset :
- Results can be fetched of the basic query, cross join query and spatial query like In, NOT, IN, Like etc.
- Arithmetic operations, geometric operations and aggregate operations can be performed through query on a dataset.
- Order by and Group by with a query can be applied on a dataset.

<br>

## Layer Visualization And Info APIs

This group consists of multiple APIs that allow users to visualise and analyse their dataset using different styles, get feature info of a feature and legends.

<img src="./images/visualization_section6.gif?raw=true" width="800px" style="margin-left:auto;margin-right:auto"/>

#### Documentation
[Contact API Support](mailto:apisupport@mapmyindia.com)

### [See Video Demo](https://www.mapmyindia.com/api/mgis-api/images/mgis/layer-visualizationandinfo-api.mp4)

These APIs form the basic foundation of geo visualisation and geo analytics.
### Get Map API
This API fetches the map tiles of an entire dataset with basic queries, queried results of cross join/spatial join between two datasets and geometric function can be performed as well.
### Get Feature Info API
This API fetches information of a feature that lies on the x and y pixel at which the user clicks. Response of the API changes based on the style that user has assigned to it.
### Get Legend Image API
This API fetches the legend of a dataset as an image which can then be used by developers on their platform to display on canvas (similar to mGIS).

<br>

## Satellite Image Segmentation API
The processing of satellite images for map representation with cutting edge CV/AI methodologies.
Our Satellite Image Segmentation API automatically categorizes things in the image and generates a map view from satellite images.

<img src="./images/11_Vision.gif?raw=true" width="800px" style="margin-left:auto;margin-right:auto"/>

#### Documentation
[Contact API Support](mailto:apisupport@mapmyindia.com)


The API detects and categorizes the below objects:
- Footprint
- Roads
- Soil
- Vegetation
- Water

User can pass set of satellite images from two different time periods to see the change in the development like building footprints and road build over time.

The Geojson output can be visualized on mGIS or any geo spatial platform to analyze.

<br>

## Raster Catalogue APIs
This group of APIS are used to fetches Raster layerlist images, legends and bounds for the particular dataset.

<img src="./images/rasterCatalog.gif?raw=true" width="800px" style="margin-left:auto;margin-right:auto"/>

#### Documentation
[Contact API Support](mailto:apisupport@mapmyindia.com)


### [See Video Demo](https://www.mapmyindia.com/api/mgis-api/images/mgis/data-operation.mp4)
<br>
For any queries and support, please contact: 

[<img src="https://www.mapmyindia.com/images/logo.png" height="40"/> ](https://www.mapmyindia.com/api)
Email us at [apisupport@mapmyindia.com](mailto:apisupport@mapmyindia.com)


![](https://www.mapmyindia.com/api/img/icons/support.png)
[Support](https://www.mapmyindia.com/api/index.php#f_cont)
Need support? contact us!

<br>

[<img src="https://www.mapmyindia.com/api/img/icons/stack-overflow.png" class="align-center"/>](https://stackoverflow.com/questions/tagged/mapmyindia-api)[<img src="https://www.mapmyindia.com/api/img/icons/blog.png" class="align-center"/>](http://www.mapmyindia.com/blog/)[<img src="https://www.mapmyindia.com/api/img/icons/gethub.png" class="align-center"/>](https://github.com/MapmyIndia)[<img src="https://mmi-api-team.s3.ap-south-1.amazonaws.com/API-Team/npm-logo.one-third%5B1%5D.png" height="40" class="align-center"/>](https://www.npmjs.com/org/mapmyindia) 



[<img src="https://www.mapmyindia.com/june-newsletter/icon4.png" class="align-center"/> ](https://www.facebook.com/MapmyIndia)[<img src="https://www.mapmyindia.com/june-newsletter/icon2.png" class="align-center"/>)](https://twitter.com/MapmyIndia)[<img src="https://www.mapmyindia.com/newsletter/2017/aug/llinkedin.png" class="align-center"/>)](https://www.linkedin.com/company/mapmyindia)[<img src="https://www.mapmyindia.com/june-newsletter/icon3.png" class="align-center"/>)](https://www.youtube.com/user/MapmyIndia/)




<div align="center">@ Copyright 2020 CE Info Systems Pvt. Ltd. All Rights Reserved.</div>

<div align="center"> <a href="https://www.mapmyindia.com/api/terms-&-conditions">Terms & Conditions</a> | <a href="https://www.mapmyindia.com/about/privacy-policy">Privacy Policy</a> | <a href="https://www.mapmyindia.com/pdf/mapmyIndia-sustainability-policy-healt-labour-rules-supplir-sustainability.pdf">Supplier Sustainability Policy</a> | <a href="https://www.mapmyindia.com/pdf/Health-Safety-Management.pdf">Health & Safety Policy</a> | <a href="https://www.mapmyindia.com/pdf/Environment-Sustainability-Policy-CSR-Report.pdf">Environmental Policy & CSR Report</a>

<div align="center">Customer Care: +91-9999333223</div>
