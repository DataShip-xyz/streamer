# streamer
Setup streaming and downloading capabilities for your profile over at dataship.xyz
# Audio, video and file streamer
Used for downloading files from dataship.xyz or Streaming them live on the website for previewing your files.

# How to use it?
clone project with, install dependencies and run it. Rename file `.env.example` to `.env` to make custom config, or just edit the source files.

# Setup
You need to add your discord (preferably your temp account that won't ever be used (not bot tokens)) Authorization token in the `.env` file
```
USER_AUTH_TOKEN=YourTokenGoesHereIn.PlainText
```

Also update the URL in `.env` file. This would be the link to your website, IP, localhost.
```
LINKSTART=http://localhost/files
```

## Side notes
If video is not playing it could be because of origin problems. Add `crossorigin=""` attribute to video tag.
PDFs only under 25MB
