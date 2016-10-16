# MultiCloud
Little project to become acquainted with Java8. Be able to search and upload files to multiple file hosting cloud providers

Will later port it via Django to create a browser based version.

The plan is to create a simple GUI that lets the user log in to their individual accounts and store
them in a salted and hashed manner on the machine for "security"

Dropbox
Google Drive
Box

After logging into each of the providers you can use a unified gui to search, view, upload and download files
across the cloud providers

Basic representation of the application is a simple directory structure where each cloud is a "root" level
directory and all of it's files are in them.

Dropbox

Google-Drive

Box

The idea is to use JavaFX, Java8 and the HTTP APIs to make it all work and then work it to the "web". Big learning experience.

Another idea is to have features such as: 
- redundant file removal
- file compression for storage based files which are "unzipped" for viewing with different compression levels for different file priorities.
- recursively detect the sizes of the directories and the files.
- file comments so that each file has "metadata" explaining what it is if necessary

Django based Python...


Start off without a framework, write everything in Python then refactor it into Django. This way I will learn how it works. Initially start off everything as a simple CLI tool then will then grow into a webapp
