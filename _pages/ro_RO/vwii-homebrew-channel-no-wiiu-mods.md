---
title: Installing the Homebrew Channel
---

{% include toc title="Tabel de Conținut" %}

This page will guide you through the process of installing the Homebrew Channel to the vWii without modding the Wii U side.

#### Section I - booting into Aroma

1. Execute the web browser exploit as [previously explained](wiiu-nand-dumper) but this time, you will need to hold the X button to open the Environment Loader menu.
2. Once you are there, boot into the Aroma environment by selecting it inside the payload loader.

#### Section II - Installing the Homebrew Channel

1. Launch the vWii Compat Installer on the Wii U menu.
2. Press `A` to install the Homebrew Channel and wait until you see `Install succeeded`. Then press the HOME button to return to the Wii U Menu.
3. Launch vWii (the Wii Menu icon).
   - If the installation has succeeded, you should see the Homebrew Channel in your Wii Menu.

You may delete the `wiiu` folder on your SD card if you so choose.

### Citire necesară

You can now use the Homebrew Channel to launch Wii homebrew apps.

Notă: Când instalezi aplicații homebrew pe cardul tău SD sau unitatea ta USB, structura dosarului tău ar trebui să arate astfel:

```
💾 SD Card
 ┗ 📁 apps
   ┣ 📁 AppName1
   ┃ ┣ 📄 boot.dol
   ┃ ┣ 📄 meta.xml
   ┃ ┗ 📄 icon.png
   ┗ 📁 AppName2
	 ┣ 📄 boot.dol
     ┣ 📄 meta.xml
     ┗ 📄 icon.png
```

`AppName1` and `AppName2` are placeholder names. Do not nest multiple `apps` folders inside the `apps` folder itself.
Do not Get confused with the `apps` folder inside of the `wiiu` folder and the `apps` folder on the root of the SD card.

[Continuați să instalați Priiloader](priiloader)<br>
{: .notice--info}
