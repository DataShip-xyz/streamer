# Streamer
Setup streaming and downloading capabilities for your profile over at dataship.xyz
# Audio, video and file streamer
Used for downloading files from dataship.xyz or Streaming them live on the website for previewing your files.

# How to use it?
clone project with, install dependencies and run it. Rename file `.env.example` to `.env` to make custom config, or just edit the source files.

# Setup
You need to add your discord (preferably your temp account that won't ever be used (not bot tokens)) Authorization token in the `.env` file
```
USER_AUTH_TOKEN=UserToken
```

Also update the URL in `.env` file. This would be the link to your website, IP, localhost.
```
LINKSTART=http://localhost/files
```

# Deploy
Deploy this app to use via the website or if you dont want to run it on your local machine to save time.


## Koyeb
[![Deploy on Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/deploy?type=git&repository=github.com/DataShip-xyz/Streamer&branch=master&run_command=yarn%20run%20start:prod&name=dataship-streamer)

Setting up env variables.

After deploying click on 'Settings'

![alt text](https://github.com/DataShip-xyz/streamer/blob/d7416882c1ba4c9bd015bf13b1ae78d617e634e3/assets/Screenshot%20from%202025-01-14%2019-41-49.png)



[![Deploy on Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/DataShip-xyz/Streamer)



## Side notes
If video is not playing it could be because of origin problems. Add `crossorigin=""` attribute to video tag.

For PDFs only under 25MB ones can be previewed.
