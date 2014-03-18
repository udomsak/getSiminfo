getSiminfo
==========

This project fork from  https://github.com/vliesaputra/DeviceInformationPlugin . Modify to support cordova plugin  use version 3.4


Note
====

For plugin i use 'reflection' for get hidden method cause Android SDK class Telephony not support DualSim ( MultiSim ) by defaut. so we need to access hidden method or predictive.

This plugin may not support All telephone i test with  Android phone 'Imobile 7.3' that base on MTK chipset and kernel compile version 'xxxxx-xxxxxxx'  

Reflection technique please use be careful due to performance. and i want to inform i'm newbie programmer this repository just want to publish hope to reduce time of Dev. 

If you like this please help me for source-code update and make the code better. 


Feature
=======

- Get SIM information for Multi-Sim ( now support 2 sim slot ) 
  - SIM Serial Number ( slot 0, 1 ) 
  - IMSIs
  - IMEIs



