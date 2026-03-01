**Contributing guidelines made by @ImagineIQ**

This is an abridged guide to contributing to the website's repository. If you want a full guide, you should visit the [discord server](https://discord.gg/gdlevels).

## Requirements

While small changes can be made directly in the GitHub web interface, it is highly recommended to use an EditorConfig capable editor such as Notepad++ or VSCode (Preferred) for larger projects and changes.

To preview changes locally, you will need Node.js, NPM, and Hugo version `0.147.8`. NPM should come with installing Node.js by default. If you want specific instructions on installing these, you should consult the full guide on Discord.

## Making Changes

The typical set of steps to contribute to anything hosted on GitHub applies: for the repository, clone the fork, cut a new branch from `master`, make and commit your changes, and submit a pull request.

The step by step process to open a cloned repository is:

1. Make a fork of the gdcs2 repository – refer to the image below.
<img width="1267" height="451" alt="image" src="https://github.com/user-attachments/assets/80fe3d2a-8131-4f5a-a3e7-e4963b4591d0" />
2. Open up GitHub desktop, the repository should be under **Your repositories.** Make sure it's selected and then press on
**Clone <Username>/gdcs2.** Afterwards a window should appear saying **Clone a repository;** You may change the local path here if you like, but for now everything else should remain the same. Press on clone to continue, this may take a bit of time.

After successfully cloning the repository, a window will appear asking how you will use the fork. Select **To contribute to the parent project** and then press continue.

There are a few options here, but the one we will be paying attention to is **Open the repository in your external editor.** In this case, we will be using VSCode. If you do not see your preferred external editor already enabled, click the options button and select it from there. Afterwards just click the **Open in <Editor>** button to get started.

<img width="954" height="582" alt="image" src="https://github.com/user-attachments/assets/7736d251-babe-472b-afc2-7941f5de2ae2" />

3. Once inside the local clone, you can install the local dependencies using the following command: `npm install`.

## Testing Changes
To run a locally hosted version of the website with your changes applied, there are a few steps. **You must first locate where the repository is in your pc.** This can be done in multiple ways depending on where you installed it to; but generally it can be found inside of the GitHub folder in documents.

Leave the file manager on the side for now, and open command prompt once again.

In order to properly run the commands needed to host the website, you will need to run command prompt as an administrator. This can be simply done by typing cmd into the searchbar, right clicking on it, and pressing **Run as administrator.** Once inside of command prompt, you need to switch the directory to the same one that the repository is in. All you need to do in order to switch directories is type `cd` followed by the file directory.

<img width="484" height="172" alt="image" src="https://github.com/user-attachments/assets/ed367c53-f137-4759-a792-428d8f9aba97" />

**Please note that the directory must be copied from inside the file, not the actual file itself.** The command should look something similar to this:

<img width="555" height="68" alt="image" src="https://github.com/user-attachments/assets/532f3bb5-6e60-422d-a322-584b1e3058f5" />

After changing the directory, run the command `npm run dev`. If all goes well, you should get a local copy of the website that updates when you make changes. **You must be able to build the site for your changes to be accepted.**

<img width="602" height="259" alt="image" src="https://github.com/user-attachments/assets/2f82820f-5c74-4903-9542-7bbb90a364d0" />

## Committing to a Branch
Committing is step one when making any pull request, and doing so is quite simple.

Upon opening up GitHub Desktop and you should see your current selected repository. Make sure gdcs2 is selected as your current repository and go to the changes tab if you aren't already there. You should see a list of the files that you have modified in the bar on the left side. That should look like this:

<img width="245" height="626" alt="image" src="https://github.com/user-attachments/assets/b2d074c3-c837-43e5-bb8b-d840def5bf86" />

If you do not see your changes, you may need fetch the origin. (Which is basically just GitHub Desktops version of a refresh.)
To commit the changes:

- Create a new branch, and make sure that everything is moved over. To do this, just press the "Current branch" button near the top, and select **"New branch."**

- select your files that you want to submit, add in a brief description in the 2nd to bottom bar, and add a full(er) description on the bottom one, then press **"Commit <number of files> to <branch>."**

After that is done, a new option should appear in the main area that says **"Publish branch."** After publishing the branch you will get the final option to preview and open the pull request. Clicking on **"Open pull request"** should bring you to the pull request window in your browser. Here, you may double check your title and description, along with submitting the actual request itself.
<img width="1326" height="692" alt="image" src="https://github.com/user-attachments/assets/a50be3f5-4f28-4bb7-929e-ba74189c12c0" />

When you are ready, just create the pull request, and that's it!
-# It may take some time for the changes to be applied as all of the commits must be manually looked over before they get accepted, so do keep that in mind.
