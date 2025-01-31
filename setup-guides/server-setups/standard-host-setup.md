---
description: Learn how to set up any of my setups on a hosting site with ease!
---

# 💾 Standard Host Setup

{% hint style="info" %}
This page walks you through setting up my server setup on the majority of server hosts. If you are using Minehut, please follow the specialised guide [here](minehut-setup.md).
{% endhint %}

## 1. Create your Zip File

Find the server files in your downloaded files from BuiltByBit or Polymart. You should be able to find the directory that looks similar to the following:

<figure><img src="../../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

Select all the files and add them to a ZIP file. I recommend using 7Zip for this, but any zipping program should work.

<figure><img src="../../.gitbook/assets/image (33).png" alt=""><figcaption></figcaption></figure>

## 2. Upload to your Server

* Once you have a ZIP file of your server files, shut down your server and connect to it via FTP or SFTP (contact your server hosting provider if you don't know how to do this).
* You then need to delete/cut all the server files out of the main directory of your server. If you want to keep these files, you'll have to put them in another folder or download them somewhere else.
* Upload your newly created ZIP file to your server host. It should be the only file on there.
* Unzip the file; it should create many files in the main directory. Once the file has been unzipped, the .zip can be deleted.

## 3. Download a Server Jar

You will now need to choose a server jar for your server to run. You can use any spigot fork you wish; however, I suggest paper for simplicity. If your server host has a built-in jar downloader, you can use that, ignore this step and proceed using that.

Download the latest **1.19.4** Paper JAR file [here](https://papermc.io/downloads/all) (Click 1.19.4 on the sidebar). and place it in your main server directory. Make sure to set the name of the server jar in the server host settings.

{% hint style="danger" %}
It is vital that your use **1.19.4** for **ALL** setups. If you use any other version, the setup will fail to load and crash. If you wish to allow connections from other client versions, you can do so with [ViaVersion](https://hangar.papermc.io/ViaVersion/ViaVersion) & [ViaBackwards](https://hangar.papermc.io/ViaVersion/ViaBackwards).
{% endhint %}

<figure><img src="../../.gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>

## 4. Plugin Dependencies

Because of licensing restrictions with certain plugins used in the setups, you will need to download some independently and add them to your `/plugins` folder. You can find links to these here:

* [TAB Plugin](https://github.com/NEZNAMY/TAB/releases)
* [Citizens Plugin](https://ci.citizensnpcs.co/job/Citizens2/)

{% hint style="info" %}
If you are setting up the Lifesteal Setup and wish to utilize the LifestealCore integration, please see the setup guide [here](../../miscellaneous/lifestealcore-integration.md).
{% endhint %}

## 5. Agree to the EULA

You will need to accept the [Minecraft EULA](https://www.minecraft.net/en-us/eula) by going into the `eula.txt` and changing `false` to `true` to start the server.

## 6. Starting the Server

You can start the server and enjoy your premade setup. Please be aware that the startup may take longer for the first time, as it needs to generate the necessary files.

Due to how pre-made server setups are created and delivered, you will probably find that when you first log in, there are a lot of plugin updates. I recommend updating these if you can to avoid any issues further down the line.

## 7. Styling your server

To obtain further information regarding server styling, rank permissions, and essential tips, kindly refer to the instructions outlined on [this](extra-information.md) page.



