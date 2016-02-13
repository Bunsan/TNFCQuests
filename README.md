# TNFCQuests
Questlines for the TechNodefirmacraft Modpack.

We are happy for players to contribute to this quest line or provide new questlines. If you wish to collaborate on this questline please read the instructions for how to do so. This is a basic run through of steps, you may need to look up more detailed instructions online.

Important Note:
- HQM quest creation can now be done offline using json files, but it is important that the new quests be added to the existing quests.hqm file using in-game commands. Completely rebuilding an quests.hqm file with all files results in the questline getting a new unique ID, meaning players using it will have their progress reset. We ask that you just provide the json files and allow us to edit the binary. Any Pull Requests with binary file changes will be rejected. We understand that final polishing of quests needs to be done in-game, so either we will complete this step or work with you to complete this step.

How to contribute

- Create a GitHub account.
- Click "Fork" in top right, this will put a copy of the repository in your account, which allows you to edit all contents.
- We highly suggest using a desktop app for interfacing with the repository. The GitHub app is decent and fairly user friendly for this type of collaboration. The app will have instructions on how to install. SourceTree is another, much more powerful app, but is more complex. I suggest the GitHub app for new users.
- You then need to clone the repository to your desktop. There are a few ways to do this. The HTTPS link or SSH method, The clone to desktop with GitHub app button or Download Zip.
- The main files are called the master branch. We highly suggest making branches for edits and testing. A branch is simply a copy of the files that are kept separate from the master branch. This will allow you to keep a master clean copy of the files while you work on new things. The Github and SourceTree apps allow you to create branches easily. When you choose the different branches on these apps the files on your computer will automatically swap to the appropriate versions.
- Now you can edit the files to your hearts content. To save the changes to your repository you want to commit them. You can do this via the GitHub app and is quite straight forward. Just add an informative commit message.
- Once you are happy with your edits you can contribute them to the official repository by Pull Request. But before doing this you want to clean it up to be just one single commit. If you don't know how to do this I'll give you the hacky easy way. If you do know how to do this, well you don't need an explanation. I suggest the hacky easy way as the proper way is quite confusing and honestly I'm terrible at it. First go into your working branch. Now copy the files you changed/added (should be just the jsons and maybe some images.) to your desktop. Go to the master branch of your repository and create a new branch. Take the files you copied to your desktop and put them into the new branch. The Github app will now show you all the changes you've made and you can commit them all in one single commit. Commit this with a message that is helpful. Now time to do a Pull Request.
- Pull Requests are probably best done via github.com. Go to github.com/yourusername/TNFCQuests from the pulldown menu select the branch you wish to contribute and click the new pull request button. Be sure you are submitting it to the master branch on this repository. Then just add a comment and submit. That should do it. 

Other Notes.
- You'll also want to keep your fork of the repository current. The way to do this is much like how you contribute. Navigate to github.com/Bunsan/TNFCQuests be sure you are on the master branch and click new pull request. Set base fork: YourUserName/TNFCQuests base: master and choose head fork: Bunsan/TNFCQuests compare: master and then create pull request, add comment and then you can merge it into your master. You can do this to your other branches as well.

- You may find you need to get the name ID of an item/block (numerical IDs will not work). The pack has MineTweaker in it, which provides a tool for getting this information. So if you are in a SSP world with cheats on you can hold the item you want the ID for and type the /mt hand command. This will give you the ID and copy it to your clipboard (you'll have to delete the < >). It also gives you the ore dictionary value if it has one.

Hope this helps you out. If you need more help, please come chat in our IRC channel. Espernet #technode. I'm always logged in, but am not always around. I do read back, but if you need my attention it is best to ping me by just including my username Bunsan in the message. I'll eventually respond, hopefully you are still around when I have time. IRC is very helpful, but don't expect an instance response.
