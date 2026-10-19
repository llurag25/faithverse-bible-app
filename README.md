# FaithVerse Bible App

A simple but enhanced Bible reader made with HTML, CSS, and JavaScript.

## Features
- Complete King James Version (KJV), Old Testament + New Testament
- 66 books, 1,189 chapters, 31,102 verses
- Book/chapter navigation
- Bible-wide search
- Favorites using browser localStorage
- Personal notes using browser localStorage
- Daily verse
- Share/copy verse
- Dark mode
- Responsive design for phone and laptop
- GitHub-ready static website

## Bible data
The app loads the public-domain KJV JSON dataset from the `midvash/bible-data` GitHub repository at runtime:
https://github.com/midvash/bible-data

Because the Bible text is loaded from the dataset, this project keeps the application code small while still providing the complete Old and New Testaments.

## Run
Just open `index.html` in a browser while connected to the internet.

For VS Code, you can also use the Live Server extension.

## GitHub Pages
1. Create a GitHub repository, for example `faithverse-bible-app`.
2. Upload `index.html` and `README.md`.
3. Go to Settings > Pages.
4. Select Deploy from branch.
5. Choose `main` and `/root`.
6. Save. GitHub will publish the app as a website.

## Important
This project uses the King James Version because it is public domain. The app is for Bible reading/study and is not affiliated with any church or Bible publisher.


## Search fix
The search function recognizes Bible references such as `Psalm 19:14`, `Psalms 19:14`, and `John 3:16`, as well as word searches. The full Bible text still requires an internet connection to load from the configured data source.
