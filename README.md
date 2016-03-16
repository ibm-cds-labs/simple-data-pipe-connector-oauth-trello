> Hey there! So you want to build your own Simple Data Pipe connector? [Start here](https://github.com/ibm-cds-labs/simple-data-pipe-connector-template/wiki/How-to-build-a-Simple-Data-Pipe-connector-using-this-template).

***


# Simple Data Pipe connector boilerplate for Trello

This [Simple Data Pipe](https://developer.ibm.com/clouddataservices/simple-data-pipe/) connector boilerplate for <a href="http://trello.com"></a> has been preconfigured for Trello API access.You can build your own special purpose connector by implementing the `getTrelloDataSetList` and `fetchRecords` methods in `lib/index.js` to fetch the desired data from Trello and optionally enrich it.

### Pre-requisites

##### General 
 A valid Trello user id is required to use this connector.

##### Deploy the Simple Data Pipe

 [Deploy the Simple Data Pipe in Bluemix](https://github.com/ibm-cds-labs/simple-data-pipe) using the Deploy to Bluemix button or manually.

##### Services

This connector does not require any additional Bluemix service.

##### Install the Simple Data Pipe Yahoo connector starter

  When you [follow these steps to install this connector](https://github.com/ibm-cds-labs/simple-data-pipe/wiki/Installing-a-Simple-Data-Pipe-Connector), add the following line to the dependencies list in the `package.json` file: 

  ```
  "simple-data-pipe-connector-oauth-trello": "https://github.com/ibm-cds-labs/simple-data-pipe-connector-oauth-trello.git"
  ```

##### Enable OAuth support and collect connectivity information

 You need to register the Simple Data Pipe application before you can use it to load data.
 1. Open the [Trello](http://www.trello.com) web page and log in.
 2. ...

### Using the Simple Data Pipe OAuth sample connector 

To configure and run a pipe

1. Open the Simple Data Pipe web console.
2. Select __Create A New Pipe__.
3. Select __Trello OAuth1.0 O Data Source__ for the __Type__ when creating a new pipe  
4. In the _Connect_ page, enter the _application id_ and _secret_ from the Trello app preferences page. 
5. Select the data set (or data sets) to be loaded.
6. Schedule or run the data pipe now.

#### License 

Copyright [2016] IBM Cloud Data Services

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
