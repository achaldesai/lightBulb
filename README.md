# Simple Phillips Smartbulb Web UI
>
> Uses Samsung's SmartThings API

<p align="center">
  <img alt="Image of implementation" src="./assets/Screenshot 2024-10-13 at 19-34-53 SmartThings Wiz Bulb Control.png">
</p>

<!--toc:start-->
- [Description](#description)
- [Pre-requisites](#pre-requisites)
- [Steps to follow](#steps-to-follow)
  - [1. Integrate Wiz Connected with Samsung SmartThings](#1-integrate-wiz-connected-with-samsung-smartthings)
  - [2. Create access to the Samsung SmartThings API](#2-create-access-to-the-samsung-smartthings-api)
  - [3. Find the deviceID for your bulb](#3-find-the-deviceid-for-your-bulb)
  - [4. Final stretch - Edit the HTML file with the newly generated SmartThings token and device ID](#4-final-stretch-edit-the-html-file-with-the-newly-generated-smartthings-token-and-device-id)
- [Features](#features)
- [Q&A](#qa)
<!--toc:end-->

## Description

This is a simple html page that lets you control your Phillips Wiz Connected LightBulb

## Pre-requisites

1. Wiz Connected App with a Wiz Connected account on your mobile device (won't work with a Guest login)
2. Samsung(SmartThings) account
3. Access to internet

## Steps to follow

#### 1. Integrate Wiz Connected with Samsung SmartThings

- Open your Wiz Connected app (current verion: 1.20.5)
- Go to the settings pane
- Go to Current home > <Home name of your device> Integrations
- In the Integrations screen click on the SmartThings icon and use your Samsung account to login and connect

> From this point you can use the [SmartThings Dashboard](https://my.smartthings.com/) to control your lights

#### 2. Create access to the Samsung SmartThings API

- Go to the [SmartThings Tokens]("https://account.smartthings.com/tokens") page
- "Generate a new token"
- Make sure to give the token a sensible name & check all permissions under "Devices" & "Device Profiles"
- Once done, "Generate Token" and save this token at a secure location. *We will need this in the last step*

#### 3. Find the deviceID for your bulb

- Go to the [SmartThings Dashboard](https://my.smartthings.com/). *It will ask you to login and device "location"*
- Find your device in the panel and click anywhere in the box.
- In the bottom left section of this screen you will find a 32 digit alpha-number code that looks like this *12a3b45c-de67-890f-12g3-h4ij5k6l789m*
- Copy this code and save this at a secure location. *We will need this in the last step*

#### 4. Final stretch - Configure the HTML

- Download the [index.html](https://github.com/achaldesai/lightBulb/blob/main/index.html) or pull this repo in your local
- Open the index.html file in a text editor of your choice. *You can use notepad if you are crazy enough*
- Go to line 45, and replace the text inside the single quotes with your SmartThings token from step 2
- Similarly, go to line 46, and replace the text inside the single quotes with the deviceID from step 3
- Configuration for the webpage is done.
- Open your favourite browser and open the index.html file by going to "file:///\<path\>/\<to\>/\<file\>/index.html"

## Features

- Turn your bulb on and off

- Adjust the brightness of the light

- Change the color of the light

## Q&A

Q: If there already exists an app to control your lightbulb, why should I use this project ?
> A: You do not have to, I made this because I did not like the bloated feeling of Samsung's SmartThings Application.

Q: How do you plan on extending this project's functionalities in the future?
> A: I do not plan to spending anymore time on this project. It does it's job quite well for me.

Q: How long did this project take?
> A: I created this in a little over an hour and half and if I can do it you can do it too.

Q: Where do I find support for this project?
> A: You don't XD.

## Thank you ❤️

#### *Reach out to me if you liked the project*
