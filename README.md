# Documentation
The belonging app is a supportive tool for litter pickers. Make a **photo**, **tag** it and **upload** it to the website.

## Contents
The documentation is part of the bigger picture, so support litter pickers to *start* and *work* with the belonging tools.
Documentation is provided as is, feel free to reach out to the team to contribute. In any way that's within your possibilities.

## Contribute
If you are a user of the app and missing some documentation, do not hesitate and reach out!<br />
We'd like to add your contributions as they are valuable for you, your companion litter pickers and us as the supportive team.

---

## About the folderstructure
There are two main folders: documentation and deploy.

### Documentation
Here is the real documentation, in different languages. Feel free to add a language, be aware to add in on all necessary locations.
Ask someone -if needed- to help with setting up the documentation.

### Deploy
We are runnning the documentation within a container. Where the documentation is build using the mkdocs method.<br />
So creating the image, there is the *build/dockerfile* for.<br />
Where the *config/nginx.conf* is used within the runtime container.<br />
Running your version of the container is possible, therefore the *run* folder is there.