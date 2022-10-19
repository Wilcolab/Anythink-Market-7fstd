# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

Step 1: Download Docker for your machine.
Step 2: Download Visual Studio
Step 3: Navigate to the folder where your anythink root folder, that you accessed in the previous step(push/pull from GitHub) is stored vy choosing File > Open Folder on Visual Studio.
Step 4: Open the terminal, you can access the terminal by choosing Terminal >  New Terminal
Step 5: On the Terminal menu > find the plus sign, click on the dropdown arrow next to it, and choose GitBash
Step 6: Start Docker, and follow its tutorial.
Step 7: Once the Docker Tutorial is over, navigate back to Visual Studio, and on the terminal type in :
        docker -v
Step 8: press Enter.
Step 9: Now type docker-compose -v.
Step 10: if you get an error about WSL2, then you can search Google for it, and download it on to your machine. 
Step 11: Now once again enter those commands, each in turn, on to the Visual Studio Terminal.
Step 12: If you are getting a BIO virtualization error, first right click on your Windows taskbar, and choose Task Manager. Under the Performance tab see if Virtualization is enabled. If it is, then skip to the next appropriate step, if not follow the next Step.
Step 13: Save your work and restart your computer and enter BIOS. (I had to keep pressing F10, but every machine is different so press the appropriate key for you.) Enter BIOS, navigate to CPU, and enable Virtualization. Save and exit.
Step 14: Now run docker-v and docker-compose -v on the Visual Studio Terminal again.
Step 15: It should be ok, next type docker-compose up. Let it run.
Step 16: If you get a daemon error, then on the Docker dashboard, open Settings. Make sure that Expose daemon on tcp://localhost:2375 without TLS is checked. Restart Docker.
Step 17: On Visual Studio, once again run docker-compose up. Hopefully it should go through.
Now navigate to the browser page your are being told to, to make sure that the front-end and back-end are working.


** After Docker download, access terminal via Visual