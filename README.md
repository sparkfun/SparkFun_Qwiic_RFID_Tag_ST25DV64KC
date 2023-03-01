SparkFun Qwiic Dynamic NFC/RFID Tag
===================================

[![SparkFun Qwiic Dynamic NFC/RFID Tag](https://cdn.sparkfun.com/assets/parts/2/1/0/5/3/SparkFun_Dynamic_RFID_Tag-_01.jpg)](https://www.sparkfun.com/products/21274)

[SparkFun Qwiic Dynamic NFC/RFID Tag (SEN-21274)](https://www.sparkfun.com/products/21274)

The STMicroelectronics ST25DV dynamic Near Frequency Communication / Radio Frequency Identification tag ICs are awesome! The ST25DV64KC offers 64-kBit (8-kBytes) of EEPROM memory which can be accessed over both I2C and RF (NFC)! It's a state-of-the-art tag which conforms to ISO/IEC 15693 or NFC Forum Type 5 recommendations. You can read and write the tag's memory using NFC even while the tag is powered down or disconnected!

The EEPROM memory can be divided into four areas, each of which can have different levels of protection applied. Want to store your data so everyone has read and write access over both I2C and RF? You can do that. In fact, that's the default! Want to store your data in an area which can only be read if you know the password, and cannot be written to (via RF)? You can do that too!

Our [Arduino Library](https://github.com/sparkfun/SparkFun_ST25DV64KC_Arduino_Library) provides all of the methods you need to read and write the user memory, control the read and write permissions, alter the area sizes and apply password control. Not only that! We've included extra methods which will let you read and write NDEF (NFC Forum Data Exchange Format) URI, WiFi and Text records which your smart phone can understand!

Repository Contents
-------------------

* /Documents - Data sheets, additional product information
* /Hardware - Eagle design files (.brd, .sch)
* /Production - Production panel files (.brd)

Documentation
-------------

* **[Hookup Guide](https://learn.sparkfun.com/tutorials/qwiic-dynamic-nfcrfid-tag-hookup-guide)** - A basic Hookup Guide for the SparkFun Qwiic Dynamic NFC/RFID Tag.
* **[ST25DV64KC Arduino Library](https://github.com/sparkfun/SparkFun_ST25DV64KC_Arduino_Library)** - Arduino library for the ST25DV64KC Qwiic Dynamic NFC/RFID Tag.
* **[ST25DV64KC Arduino Library Documentation](https://docs.sparkfun.com/SparkFun_ST25DV64KC_Arduino_Library/)** - A full library use overview, API reference guide and key example walk-through.

Product Versions
----------------

* **[SEN-21274](https://www.sparkfun.com/products/21274)** - Initial SparkFun version release
* **[SPX-19035](https://www.sparkfun.com/products/19035)** - Initial SparkX version release

License Information
-------------------

This product is _**open source**_! 

Please review the LICENSE.md file for license information. 

If you have any questions or concerns on licensing, please contact technical support on our [SparkFun forums](https://forum.sparkfun.com/viewforum.php?f=152).

Distributed as-is; no warranty is given.

- Your friends at SparkFun.
