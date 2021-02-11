# Ubuntu-Grdp
## Set GitHub Config

1. Edit `GitHubMail` and `GitHubMail` in .github/workflows/Ubuntu.yml

2. Add a personal access token from https://github.com/settings/tokens and add as `GH_TOKEN` in repo secrets

## Set SSH Tunnel:

1. Add your ngrok authtoken as `NGROK_TOKEN` in the Repository Secrets

   > You can find this token here: https://dashboard.ngrok.com/auth/your-authtoken

2. Add a shell login password as `SSH_PASSWORD` in the Repository Secrets

## Set Remote Desktop:

1. Visit here https://remotedesktop.google.com/headless

2. Copy debian Code From website

3. Then fork this repo

4. Go to actions 

5. Click on Run WorkFlow

6. Replace " paste your code here " with the whole code that you just coppied 

7. Now just Run the WorkFlow

8. Find your rdp here https://remotedesktop.google.com

## Default pin is 123456 

You can also use chrome remote desktop apk


#### have a Good day :)

Note: This is just for Testing and Deployment of Applications, and Debugging Purpose. I do not encourage to misuse of Github Actions! Thanks © [Area69Lab](https://t.me/Area69Lab)
