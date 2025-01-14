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


Then scroll down and expand the option 'Environment variables'
![alt text](https://github.com/DataShip-xyz/streamer/blob/d7416882c1ba4c9bd015bf13b1ae78d617e634e3/assets/Screenshot%20from%202025-01-14%2019-42-16.png)

Click on 'Raw editor'
and paste the lines in the below format (with your user token and url)
![alt text](https://github.com/DataShip-xyz/streamer/blob/d7416882c1ba4c9bd015bf13b1ae78d617e634e3/assets/Screenshot%20from%202025-01-14%2019-42-49.png) 

After setting your env variables click on 'Save and deploy'

![alt text](https://github.com/DataShip-xyz/streamer/blob/e1a2ab4bf2b976e3f4d6601d442c59ec983352ff/assets/Screenshot%20from%202025-01-14%2019-55-18.png)

## Render
[![Deploy on Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/DataShip-xyz/Streamer)

After deploying onto render go to https://dashboard.render.com
When there click on 'Projects' in the panel on the left side
Move down and click on your service 'your_service_name' (streamer)

On the left panel click on 'Environment' and then click 'edit' on the right of Environment Variables.
![alt text](https://github.com/DataShip-xyz/streamer/blob/859775050966081203487910428075ddbc1167eb/assets/Screenshot%20from%202025-01-14%2019-58-48.png)![alt text](https://github.com/DataShip-xyz/streamer/blob/859775050966081203487910428075ddbc1167eb/assets/Screenshot%20from%202025-01-14%2019-59-19.png)

Move down and click on 'Add from .env'
![alt text](https://github.com/DataShip-xyz/streamer/blob/859775050966081203487910428075ddbc1167eb/assets/Screenshot%20from%202025-01-14%2019-59-41.png)

Paste your .env lines in the below format (with your user token and url). Then click on 'Add variables' to save addtions.
![alt text](https://github.com/DataShip-xyz/streamer/blob/859775050966081203487910428075ddbc1167eb/assets/Screenshot%20from%202025-01-14%2020-00-34.png)

After setting your env variables move down and click on 'Save, rebuild and deploy'

![alt text]([https://github.com/DataShip-xyz/streamer/blob/e1a2ab4bf2b976e3f4d6601d442c59ec983352ff/assets/Screenshot%20from%202025-01-14%2019-55-18.png](https://github.com/DataShip-xyz/streamer/blob/859775050966081203487910428075ddbc1167eb/assets/Screenshot%20from%202025-01-14%2020-01-00.png))


## Side notes
If video is not playing it could be because of origin problems. Add `crossorigin=""` attribute to video tag.

For PDFs only under 25MB ones can be previewed.
