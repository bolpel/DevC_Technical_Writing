# [title:How to Git on Phone]
— *a beginner's guide to using git on mobile phone.*

![Hero-banner](file:DevC_Technical_Writing/PocketMark/Src/Attachment-2025-08-20.png)

A lot of times, I have had people complained about how not being able to use git is one of their major setback as a learner using phone. 

In this guide, you are going to learn, step-by-step, how you can use git on your phone without _breaking anything or rooting your phone_. And of course, the steps you are going to take to achieve this do not require you to be a technical expert 🧑‍🔧. If you can follow this guide to the end, you are as good as writing your first ```commit```  && ```push``` your work in no time. 

## Requirements
Prepare the following;
- Smartphone 📱
- Internet 🛜
- Your curiosity 🤨

## Step 1: Install Termux
The first thing we want to do is install the essential app.

![termux-screen](file:///storage/emulated/0/Documents/PocketMark/Src/image_1755705926520.png)


**Termux** is the main app we need to carry out `git` operations on our phone. **Termux** is an open source android terminal emulator that allows you to run linux commands without requiring any _hardcore setup_ or _rooting your phone_. However, it can only be installed conveniently through these two locations:
   - You can get it on the termux official [website](https://termux.dev/en/) or
   - through [F-Droid](https://f-droid.org/) an app store to anything thing free and open source.
## Step 2: Setting Up Termux

![termux-installed](file:///storage/emulated/0/Documents/PocketMark/Src/Attachment-2025-08-20_4.png)


We are done with the installation of Termux. Now,  we are going to setup our termux to be able to access our phone storage. Start your Termux and type the following;
                  `termux-setup-storage`.
Follow the prompt to enable permission to allow `Termux` access your phone file storage. If this works fine you should have a `storage` when you do `ls`. 

![storage-setup](file:///storage/emulated/0/Documents/PocketMark/Src/Attachment-2025-08-21.png)

In order to access your file manager enter `shared` where the file is located via `storage`.

```script
~$ cd storage
~/storage $ cd shared
```     
       
![storage-accessed](file:///storage/emulated/0/Documents/PocketMark/Src/Screenshot_20250820-200309.png)


## Step 3: Install Git
The next step is to install git. You can use either of these codes `apt install git` or `pkg install git` to get git installed. Check if you successfully installed git ```git --version``` or ```git -v```.


![Git-version](file:///storage/emulated/0/Documents/PocketMark/Src/Screenshot_20250820-214909.png)




## Bottlenecks
In the course of your installation you might encounter issues like **bad mirror** , **outdated package** or **missing libraries** etc.  You can try the following options;
1. **Change repository:** choose from list of repos across the globe.
```termux-change-repo```
2. **Update or Upgrade:** try either of the following `commands`
```bash
pkg update -y  && pkg upgrade -y 
apt update -y  && apt upgrade -y
```
3. Ensure all the `commands` are entered appropriately.


### Conclusion
Congratulations 🎉, you just reached another milestone in your tech journey. Break barriers with your phone by completing your assignments and push your work. Git on phone works exactly as it would on PC. 

#### Disclaimer: this guide for education only and its focus is to show you a work around using your phone as a terminal should you find yourself in a situation to need it. It is not in anyway assume your phone as the best option for your tech journey.


**Are you just starting out?** Check out my [beginner's guide](#) as a first time `git` user. 


Enjoy `gitting` 👌

**Learn more about Termux** [here](https://wiki.termux.com/wiki/Main_Page)
