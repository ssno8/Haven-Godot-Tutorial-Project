# Haven Godot Tutorial Project

Hello everyone and welcome to the Godot Game Creation Guide! I’ll be stepping through how to create your own Godot game. Here is the Google Doc where there are visual gifs of each step: [HERE](https://docs.google.com/document/d/1vtFwGXilsL1gE8R1BpnMGBLEBqEZLJ6FgjZ6FDvyFQo/edit?tab=t.0)!


## Download Software
First of all, you need to download the required applications!
1. **Download Github Desktop**
  - Search up Download GitHub Desktop in your preferred search engine and it should be the first link that appears. Alternatively, you can [click here](https://desktop.github.com/download/) to download the desktop version of GitHub. You will need to create an account if you don’t already!
2. **Download Godot**
  - Search up Download Godot in your preferred search engine and it should also be the first link that appears for your type of device (Windows, Mac, Linux). Alternatively, you can [click here](https://godotengine.org/download/) to download the latest version of Godot.

## GitHub Setup
Now that we’ve gotten the two applications needed to create the game, I’ll show you how to format your GitHub to upload your Godot game!
1. **Create a New GitHub Repository**
- In your desktop GitHub application, create a new repository by clicking File in the top left hand side.
2. **Name Your Repository**
- Your repository is like your “root” folder, so you would want to name it something appropriate and not confusing. An example of naming your repository could be “Haven Godot Tutorial Project” however you would change “Haven Godot Tutorial” to the name of your game. This is where your Godot game files will live!
3. **Local Path**
- Your repository should be saved somewhere easily accessible on your device. An example is creating a Godot folder where all game related repositories for the game will be (e.g. C:\Users\username\Documents\Gotdot Projects and then the repository will save in the folder like C:\Users\username\Documents\Gotdot Projects\name-of-your-project which is now your local file path).
4. **Settings**
- Ensure you click on Initialise this repository with a README, click on Git ignore and either scroll or type Godot and select it. Once you have completed that, click Create repository.
5. **Final Step!**
Click on Publish repository and make sure to uncheck Keep this code private so that your code is public (as per Hack Club requirements).

And voilà! You now have a GitHub repo where your Godot game will live!

## Godot Setup

Now that you have a GitHub repository set up, you can create your Godot game! The reason you should do this is so that you can constantly commit updates in your game and it saves you from any unprecedented corruption (which has happened in previous gamejams). This way you are able to go back to the latest commit rather than restarting all over again! Here are the steps to store your game in your GitHub repository.

1. **Open Godot**
- Self explanatory, open Godot.
2. **Create Game File**
- In the top right corner of the application, click on Create.
3. **Name Your Game**
- Give your game a name!
4. **Project Path**
- Search for the repository in your file library and select it.
5. **Create Your Game!**
- Click on Create.

And voilà! You now have created the Godot game files. Congratulations!

## Game Creation
I will not be going through how to actually start creating the game. Here is another guide on how to start making your game courteously made by Lexy :) which you can [access here](https://gist.lexy.boo/lex/godot-tutorial)!

Once you have created your game using Lexy’s tutorial, it’s time to export and ship (upload playable game onto Itch.io).

## Export Game
Time to export your game! As you have most likely just downloaded Godot, export templates are probably not downloaded. Let’s download it now.
1. **Download Templates**
- On the top left corner of the application, hover over Editor and then click on Manage Export Templates, and then click on Install All Templates. It will take a minute to fully download.
2. **Getting Ready to Export**
- Once the templates have downloaded, head over to the Project button in the top left corner, click on Export, click on Add and then click on Web.
3. Exporting Your Game
- Now, you must click on Export Project, name the file index.html (THIS IS VERY IMPORTANT AND THE GAME WILL NOT RUN IF IT IS NOT NAMED index.html), create a new folder called export and save your index.html in the created folder.
4. **Zip Your Export File**
- Head into your library and search for your repository game files. Find the export folder, Zip it and name it.

And that’s all the Godot stuff done! Yippee :D 
**QUICK NOTE I WANT TO ADD: Continuously commit your updates in GitHub, it doesn’t matter how many times you do it. If you think “hmm should I commit my project?” the answer is YES, KEEP DOING IT!**

## Shipping Game to Itch.io
Last part, time to Ship your game to Itch.io!

1. Go to Itch.io
- Self explanatory, and create an account if you haven’t already.

2. Adding Details + Uploading
- Add the title of your game.
- You can edit the game link.
- Make sure the Kind of project is set to HTML to make it web playable.
- Make sure the Pricing is set to No payments as issues may arise if you use other options.
- Find the location and upload the Zip file you created in the last Godot step (AGAIN MAKE SURE THE .html IS NAMED index.html OR IT WILL NOT WORK).
- Ensure you have This file will be played in the browser checked off once the Zip file finished uploading (forgot to do that in the gif below, sorry T^T).
- Set your viewport size to the same as your game so that it actually works, looks nice, and makes sense. You can find the viewport of your game by navigating to your Godot game -> click on Project -> Project Settings -> look for Window under Display -> the height and width of your game should be the first thing to pop up when clicking on it.
- Ensure you have the Fullscreen button and SharedArryBuffer support checked off under Frame options.
- Add a description of your game (e.g. what it is about, what keys are compatible, how to play).
- You won’t be able to publicly publish the game until you have submitted it as a Draft first, had a play through to make sure all mechanics are working as intended, then you can go back and submit it publicly.


CONGRATULATIONS! YOU HAVE JUST COMPLETED THE GODOT GAME GUIDE AND HAVE A FULLY PLAYABLE GAME FOR ANYONE TO ENJOY :D You are now an expert and can effectively start creating your game to exporting it onto Itch.io! I hope this tutorial helps and if you have any further questions or concerns, please don’t hesitate to reach out to one of us organisers!

MADE WITH LOVE, KING BNE ORG :) 
