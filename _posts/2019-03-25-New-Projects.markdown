---
layout: post
title:  "New Projects"
categories: Project Updates
---

# New start + s...

I started 2 new different projects. One being the game project with a game engine called 'Unity'. The other one being my own smartwatch project using Arduino Pro Mini.

**Unity Project**
I didn't have a lot of time to spend on this project but I already got my ideas clear. It's going to be an RPG or a TPS(*Third person Shooter*) or Top Down Shooter (I have still not yet decided.). This RPG takes place in a medieval environment with a bit fantasy aspect. Which means that the player will be fighting with swords, wands (through magic) etc. I've already found good models/animations from online which I can use it for free if I don't put my project commercially.
At the very beginning, I'm thinking of a some sort of cinematic view, where the background story will be explained. After that player will be either spawned in a town where there's going to be a castle near by (the castle will be the source of the quest in the beginning) or a special area. This will be dependent factor by the class they pick (Mage, Swordsman, etc.).
I'm still unsure about the classes in the game. At the moment, I'm thinking of a "skill-based classes", which means that players won't be able to pick their classes in the beginning of the game, rather they will pick throughout their game by choosing different types of skills, which will lead players to have their own custom classes. I'll also be adding special passive effects if they learn certain skills together.

**Smartwatch Project**
For the past 2 weeks, I've been working on a smartwatch project using my Arduino Pro Mini 3.3v (*ATMEGA328P @ 8Mhz*). My intention is that my smartwatch will connect to my phone and then receive all the data such as time information, notification from it. As it also receives time information, it does not need a RTC (*Real Time Clock*), benefitting the size of the smartwatch. For the bluetooth module, I used HM-10 clone, which is a BLE(*Bluetooth Low Energy*) module. During the development process, I realized one unfortunate thing. My HM-10 clone *ONLY* supported BLE. Any legacy bluetooth connection technology was unsupported. Therefore, I had to create myself an app just to connect to my device and send information. (I was going to make an app for my smartwatch anyway, but process of developing an app was a bit harder since there wasn't a lot of tutorials on how to connect to a BLE device using Android Studio online.) There is a HM-10 firmware update, which would allow legacy bluetooth technology, but because of the fact that I have the clone HM-10, it didn't work. Other than that, I used an 128x64 OLED display (SSD1306), vibrator (vibration motor), a push button for executing simple task within the watch (turning the screen on when it's in sleep to check time, etc.), a switch to power the device on, an apple watch 4 wrist band/case for the casing and 150mah 3.7v battery for powering the whole device.
I've already got the time working correclty as well as it notifies me when I receive a notification in my phone (although it doesn't display from which app the notification was sent from, nor the details of the notification). Here's a quick demo of my smartwatch:
https://youtu.be/OTAluK8UKLc

I'm still undone with my smartwatch and I'll still improve the software and battery life as it doesn't last long (according to my calculations, around half a week). I'm also planning a smartwatch v2, which would use ATTiny85 as the smartwatch I made turned out to be wayy too "fat". Haha. But that won't happen in the near future.
