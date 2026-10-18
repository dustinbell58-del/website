# Fourth Coast Contractors website

Everything is in one flat folder, so you can drag all of it into a brand new GitHub repository at once. No folders, no build step.

## Files
- index.html : the website
- styles.css : design and Ohio State colors
- main.js : mobile menu and footer year
- logo.png, favicon.png : your logo
- img-*.svg : original illustrations for each service (sharp at any size)

## Publish in a fresh repository
1. Sign in at github.com, click the + at the top right, then New repository.
2. Name it fourth-coast-contractors, choose Public, and click Create repository.
3. On the new empty repository page, click "uploading an existing file".
4. Unzip this download, select ALL the files inside, and drag them into the browser window. Wait for the uploads to finish.
5. Click Commit changes.
6. Go to Settings > Pages. Under Build and deployment, choose "Deploy from a branch", pick main and / (root), and click Save.
7. After a minute or two your site is live at https://YOURUSERNAME.github.io/fourth-coast-contractors/

index.html must be at the top level of the repository, not inside a folder.

## Replace an illustration with a real photo
Save your photo as a .jpg, then in index.html change the matching img src (for example src="img-heating.svg" to src="my-furnace.jpg") and upload the photo to the repository.

## Contact form
The form opens the visitor's email app. To receive submissions directly, make a free form at formspree.io and change the form tag's action to your Formspree link.
