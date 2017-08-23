# ascii_art_gallery
Platform to share your ascii art built using  the Google App Engine datastore and Jinja template engine

## Accessing the demo<br /> 
https://asciiart-177120.appspot.com/

![ascii](https://user-images.githubusercontent.com/17767383/29434455-af7d9cf2-8368-11e7-945c-edbc5439d2fe.png)

## Running a development version

### Requirements

- Google App Engine SDK for Python <a href="https://cloud.google.com/appengine/downloads#Google_App_Engine_SDK_for_Python">Download and install instructions</a>
- Clone this repository: ''' git clone https://github.com/as409/ascii_art_gallery '''

### Run a development instance

- Run dev_appserver.py . within the source directory
- Go to http://localhost:8080 in your browser
- Browse the application. Any edits to source files should reload the server automatically.

## Deploy to an App Engine instance

- Create a new project on cloud.google.com
- Run the command ''' gcloud init ''' and select the desired project
- Deploy with ''' gcloud app deploy app.yaml ''' (<a href="https://cloud.google.com/sdk/gcloud/reference/app/deploy">See the documentation)</a> in the source directory

