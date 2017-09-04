This is a Hello World app using python3 and tensorflow for google app engine flexible environment

## Run Locally

1. Clone this repo.

   ```
   git clone httpsgithub.comGoogleCloudPlatformpython-docs-samples.git
   cd python-docs-samplesappengineflexible
   ```

2. Open a sample folder, create a virtualenv, install dependencies, and run the sample

   ```
   cd hello-world
   virtualenv env
   source envbinactivate
   pip install -r requirements.txt
   python main.py
   ```

3. Visit the application at [httplocalhost8080](httplocalhost8080).


## Deploying

1. Use the [Google Developers Console](httpsconsole.developer.google.com)  to create a projectapp id. (App id and project id are identical)

2. Install the [Google Cloud SDK](https://cloud.google.com/sdk/), including the [gcloud tool](https://cloud.google.com/sdk/gcloud/), and [gcloud app component](https://cloud.google.com/sdk/gcloud-app).

3. Setup the gcloud tool. This provides authentication to Google Cloud APIs and services.

   ```
   gcloud init
   ```
   
3. Use gcloud to deploy your app.

   ```
   gcloud app deploy --project <your-app-id>
   ```

4. Congratulations!  Your application is now live at `your-app-id.appspot.com`


## Licensing

Licensed under the Apache License