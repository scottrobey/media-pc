# media-pc
Contains documentation and setup files for my home media PC.

## The Hardware

I'm using: 

If you're planning on gaming get a higher end mini-PC, otherwise you probably don't need to and can get a good mini PC that would be sufficient for around $200-$300

## Operating System - Windows (Linux coming later...)
Try with Windows first
Try with a Linux OS ideal for media and/or gaming
Dual-boot?
Compare gaming performance

### Windows Setup
Initial win setup - may want to not set a password when creating a user. Or better would be to create a new user with limited permissions that doesn't need password


1. Install Brave browser
   a. screen shot
2. Disable windows lock screen
   a. screen shot


For Windows 10 Pro, Enterprise, or Education, you can use the Local Group Policy Editor. Press Win + R, type gpedit.msc, and press Enter. Navigate to Computer Configuration > Administrative Templates > Control Panel > Personalization. Double-click on "Do not display the lock screen," set it to "Enabled," and click OK. This will disable the lock screen on startup and reboot.

3. Configure power mode settings and screen and computer sleep
Screen timeout
Device sleep
Power mode? May want to change this according to needs

#### Add Programs to Launch at Startup
📺 Bonus: Auto-Start Media Mode on Boot (Windows)
Press Win+R, type shell:startup, hit Enter

## Brave

Brave is what we primarily use to access streaming and other sites due to it's superior ad blocking and ease-of-use. I don't actually know if we lose much in the form of picture or audio quality compared to using the native desktop apps, but something to look into

On desktop create a folder names "Streaming Sites"
Create shortcuts for all of the streaming sites - click and drag from the dots to the left of the website address to the desktop
Place Brave shortcuts for your streaming sites on your desktop in a folder named "Media Center" (or whatever you want).
Create good icons for the shorcuts, see: icons folder 


Using the steps listed above to "Add Programins to Launch at Startup" add a shortcut to this folder in the startup folder and the folder will be opened automatically when your Mini PC starts

Inside Brave:
 * F11 to go full screen
 * Use Brave Password manager?

Show bookmarks toolbar - ctrl+shift+b
Import bookmarks - can export from my env first. this repo has bookmarks included you can import
Create a bookmarks folder for streaming or other sites

## Best Apps & Websites for streaming Free TV
Tubi
Roku Channel? https://therokuchannel.roku.com/
FreeVee?
Create free accounts to get access to more content!

Where to watch sports and live TV? CBS / NBC / ABC websites?

## Gaming

What new games can we expect to play?

Retro gaming!

## Remote
Air mouse 1st

Bluetooth keyboard with built-in mouse as a back up

How to administer remotely Windows remote setup 


## TODO


 * Setup GitHub repo for this - public
 * Add icons to GitHub
 * Add bookmarks
 * Maybe a setup script?
     * This would be easier in Linux using CM tool to install and configure various apps


...Later

Network Setup - ethernet obviously preferred but not required?

Plex Server?? Accessing when off the network?

DVR?

Audio?

Resolution and image quality differences?

Running LLMs locally?! Not really related to being a media center
Other cool things you can do with your mini PC


## Setup an AI Assistant
How can we leverage an AI assistant to make media player experience better?
At a minimum, an LLM can help answer questions you have about setting up your PC to be a media center, and also has some good ideas for cool things you can do. Interesting prompts: ToDo
