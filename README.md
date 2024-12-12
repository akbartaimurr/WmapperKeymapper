<p align="center">
  <img src="https://github.com/user-attachments/assets/614ac46c-4635-47e0-94da-a4e9f0cee203" alt="Image description" width="500">
</p>

<p align="center">
  <a href="https://yourwebsite.com" target="_blank">
    <img src="https://img.shields.io/badge/✨%20Website-black?style=for-the-badge&logo=firefox&logoColor=white" alt="Website">
  </a>
  <a href="https://yourwebsite.com/about" target="_blank">
    <img src="https://img.shields.io/badge/❓%20About-black?style=for-the-badge&logo=firefox&logoColor=white" alt="About">
  </a>
  <a href="https://yourwebsite.com/downloads" target="_blank">
    <img src="https://img.shields.io/badge/🔽%20Downloads-black?style=for-the-badge&logo=firefox&logoColor=white" alt="Downloads">
  </a>
  <a href="https://yourwebsite.com/build-installation" target="_blank">
    <img src="https://img.shields.io/badge/👩‍💻%20Build%20Installation-black?style=for-the-badge&logo=firefox&logoColor=white" alt="Build Installation">
  </a>
  <a href="https://yourwebsite.com/documentation" target="_blank">
    <img src="https://img.shields.io/badge/📜%20Documentation-black?style=for-the-badge&logo=firefox&logoColor=white" alt="Documentation">
  </a>
</p>

<p align="center">
  <a href="https://yourwebsite.com/support" target="_blank">
    <img src="https://img.shields.io/badge/❤️%20Support%20the%20Project-white?style=for-the-badge&logo=none" alt="Support the Project">
  </a>
</p>

<!-- Add the new image with appropriate spacing -->
<p align="center" style="margin-top: 20px;">
  <img src="https://github.com/user-attachments/assets/5892b3d2-251a-4146-8409-7c8e948ad392" alt="Second Image" width="1000">
</p>


## Key Features

* Keymap all through out windows
* Swiping Keymaps
  - Allows you to simulate a swipe using [coordinates + radius = swipe]
* Normal Keymaps  
* Set delay before keymap takes action
* [WSA] (https://github.com/MustardChef/WSABuilds?tab=readme-ov-file) Support
* Import Keymap configuration file [NEW]
* Users can create their own keymap config files[NEW]

## How To Use [outdated] [before 1.0.3]

### -------> Default Mode <-------------------------
 - Type 'Create' on the Enter a command prompt
 - Enter key you want to assign for the click, for example If I want key W to simulate a click somewhere, I'll choose W
 - If you type Q in that prompt it won't quit the app but instead finalize the config you made
 - Once done choosing a key, move your cursor to a place on your screen and click S on keyboard, This place is where the click will be simulated
 - Once cords are saved, It will prompt to Enter another key for next click
 - You can either make more or type q and finalize it
 - Once finalized, test it out by pressing on the key you chose, In this example it was W

### -------> Swiping Mode <-------------------------
 - Type 'Create' on the Enter a command prompt
 - Enter key you want to assign for the click, this will be the key which when pressed, simulates a swipe from start location to end
 - If you type Q in that prompt it won't quit the app but instead finalize the config you made
 - Once done choosing a key, move your cursor to a place on your screen and click S on keyboard, This will be the start location for swipe
 - Once cords are saved, It will prompt you to enter what type of swipe you want
 - Choose one [ex. up,down,left,right]
 - It will now prompt you to enter a radius for the swipe
 - The radius is basically the distance from the starting point to another point, For example, If my cords are [x,y] It will add a radius of in this example I'll use 200, It will add 200 to the cords to find end point.
 - A radius of 200 is recommended by the way
 - Now you are going to enter the speed, This will be the duration it takes for your cursor to swipe from Point A to Point B
 - A speed of 0 seconds is recommended for no delay
 - Once done, It will prompt to enter another key for another swipe
 - You can either make more or type q and finalize it
 - Once finalized, test it out by pressing on the key you chose, It should now swipe from your starting point to another point which is the added radius point

### -------> ImportConfig Command <-------------------------
 - Import config is a new feature introduced in 1.0.1, it let's users directly import their keymap config from the directory without having to create keymaps all over again
 - To import a keymap configuration you can use the 'importconfig' command
 - Type 'importconfig' followed by a json file name with content inside
 - The JSON config should be in the same directory as what you are using:
 - 
   ![image](https://github.com/FlippantDev/Wmapper/assets/134905706/c57af3f2-74ef-48a2-bd35-678f523438d3)

 - So now I will type 'importconfig keymapconfigdemo.json'
 - The JSON file in the photo is already premade for use, you can edit it if you want
 - Once you type it in and enter, it will register and the program will start listening


> **Note**
> This may not apply to future versions so I will try to keep this documentation updated for next versions






## Download 

You can download Wmapper ⚡ from the Download Center which is the [Github Releases Area](https://github.com/FlippantDev/Wmapper/releases/)
Join the discord for support : https://discord.gg/wgTeTeDS

## Demo

https://www.youtube.com/embed/nbZdMVVyTG4?si=3MrZyNSGP9TGjhN4


---

## Related

[wmapper-web](https://wmapperonline.web.app) - Official Website for Wmapper
[Windows Subsystem For Android Builds](https://github.com/MustardChef/WSABuilds?tab=readme-ov-file) - Wmapper was programmed esentially for this and to perform amazing on this 😎


## You may also like...

- [WSA toolbox]([https://github.com/amitmerchant1990/pomolectron](https://apps.microsoft.com/detail/9PPSP2MKVTGT?hl=da-DK&gl=CN)) - A toolbox for WSA

## License

Apache 2.0

---

> [flippantagain@gmail.com]
> Youtube [@urdadflip](https://www.youtube.com/channel/UCE-ixwTDDLOqRPz3InkWPYw) &nbsp;&middot;&nbsp;

