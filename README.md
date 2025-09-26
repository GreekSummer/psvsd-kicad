# PSVSD KiCad source

This is a fork of [Yinfanlu's PSVSD adapter](https://github.com/yifanlu/psvsd/). Its main purpose is to adapt the original Eagle Autodesk files to KiCad, which is open source and free. 

The conversion was done using KiCad's own importer. The result was mostly complete with various issues that had to be manually corrected. The result has not yet been produced, so assume there are still issues.

I removed the debug headers to simplify the board. Most people do not need these. I also replaced the SD slot with one that is easier to find and source.

A big problem with these is sourcing the main USB-to-SD IC. As of August 15th 2025, I was able to find the GL823A-QFN24 on AliExpress for $3.30 per IC. The rest of the parts cost ~$5.03 on DigiKey.
