mi-home-android project
=======================

Special thanks go to https://xiaomi-miui.gr for inspiration. Also thank you to yAuMe, John.Doe, reggaemanu for their support and feedback.

Update
======
2016-10-09	MiHome 3.9.5

2016-10-07  MiHome 3.8.11

Purpose
=======

This project intends to provide a multilingual version of Mi Home on Android devices.

Mi Home is a global application which can support many Xiaomi devices. For each device, a plugin is downloaded. Global application and plugins are almost written in Chinese, which is quite confusing for me :)

So I want to provide translation for the global application and plugins.

Installation of Mi Home
=======================

I'm currently working on Mi Home 3.9.5.

The official application manages its plugins from protected storage which is only accessible from rooted devices.

The only modification I have made to the official application is to handle plugins from a public storage. They are now available in a folder called **MiHomePlugins** next to usual **Download**, **Movies**, **Music**...

Prepare your phone or tablet
----------------------------

By default, when no plugin is available, the main application will download them and put them inside **MiHomePlugins** folder. Each device model has a unique identifier, and plugins are actually **APK** files.

````
MiHomePlugins
  110                          Mijia 360 identifier
    4095.apk                   Plugin for Mijia360
110_strings.xml                Chinese template to translate
MiHome_3.9.5_multi.apk        Modified MiHome application to install
README.md                      This README file
````

All you have to do is to copy the **MiHomePlugins** of this repository into your phone or tablet, and then, Mi Home should be translated :)

Available languages
-------------------

For now, there is no language available.

I currently provide Chinese template for French and English translation. Each Chinese string is prefixed with a number to help "in context" translation.

I will soon provide French and English, stay tuned :)

If you want to help, you can translate **110_strings.xml** in any language you want, and I will integrate it.

