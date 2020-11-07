# minecraft_data Project

**This readMe file explains:** 
1. The contents of the project/repository 
2. Contains instructions for setting up the minecraft server for the first time 
3. For running the server regularly after setup

## 1. Project Contents
This repository holds all of the minecraft server data. This is all the files that hold what we've built in our world, what items our players have, and other server specific things such as the server plugins.

## 2. Setting up the Server
1. Download and Install [Git]()
2. Download and Install [Docker]()

**Instructions for Windows continued:**

3. Open a command prompt window (type `cmd` into search bar) *Note: You may need to right click and open as an administrator*
4. Type `sysinfo` and press enter. You should see a long list. In this list there is an item that should have `firmware` and `virtualization` or `Hyper-V` in the name. Check whether the item called something like `Virtualization in Firmware` is `true` or `enabled`. If it's `false` or `disabled`, you need to go into you PC BIOS. I (JattMones) am happy to help you with this part over the phone, it's not a bad idea to have a second oppinion before you change or click anything in the BIOS. Once this is set to `true` or `enabled`, continue with the set-up.
5. Open another administrative CMD window and type `cd %user_profile%`
6. Type `mkdir minecraft_server` and press `enter`
7. Type `cd minecraft_server` and press `enter`
8. Type `git clone https://github.com/JattMones/minecraft_data.git` and press `enter` 
9. After this finishes type `cd minecraft_data` and press `enter`
10. Type `git checkout master` and press `enter`
11. Type `git pull` and press `enter`. *Note: This first clone will take a long time to copy all server files 30-60min*

**YAY! You've successfuly have the server data! Now onto setting up a docker container to run the server**
