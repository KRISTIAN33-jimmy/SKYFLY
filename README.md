# Di Sipio SKYS — deploy in two easy steps

1. Create an empty GitHub repository, then use **Add file → Upload files** and upload every item inside this folder.
2. In Netlify choose **Add new project → Import an existing project → GitHub**, select that repository, and deploy with the detected settings.

This GitHub-to-Netlify route is required because the image/PDF reader uses a Netlify serverless function. Netlify automatically rebuilds it whenever you upload an update to GitHub.

Open the deployed site, visit Control Centre, add an OpenAI API key, choose the model and then import the timetable.
