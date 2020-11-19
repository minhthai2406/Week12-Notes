# Week 12 Personal Notes

## How to create README file and edit it
- use touch to create file, touch README.md to make a blank readme file
- use nano to open README.md file

## How to create a new file
- when making a new file on the computer, first you save, then you stage, then you commit
- cat "file name" to read the file
- nano "file name" to edit the file
- git log to see log changes

## How to push your project to GITHUB
- git remote add origin "url here"
- git branch
- git push
- git commit -m "description of the changes"

## How to fix the error "Fatal: remote origin already edxists"
- git remote set-url to fix remote origin already exists

## How to edit and update files from terminal to GITHUB
- nano filename
- git add filename
- git commit filename
- git push
- only need git push to update changes to github

## How to paste URL in Terminal
- you can paste url with right click

## How to clone someone project
- git clone (url) to copy someone codes
- pull request to ask owner to pull in the codes

## How to save credential in cache for 15 minutes
- This will allowed Git to save your password in memory for some time.
It's important to know that saving credential in Git will save your credential in a text file that is public to everyone to view, therefore setting a cache timeout to delete after a certain period of time is important.

Set git  to use the credential memory cache

``` git config --global credential.helper cache ```

By default, Git will cache your password for 15 minutes.
You can also set it to 1 hour long by setting cache timeout to 3600.

Set the cache to timeout after 1 hour (setting is in seconds)

``` git config --global credential.helper 'cache --timeout=3600' ```

## Change log
- Added credential memory cache
