EN|[中文](README_zh-cn.md)
# JS to TS
Well,maybe it is useless.
# Cmdids Extraction Tool
This is a Genshin cmdids Extraction Tool.  
Warning: Please put all proto files in./proto/ directory, otherwise the tool will not run.  
Before you start, make sure nodejs is installed. If you haven't installed it, you can download it [here](https://nodejs.org/).  
# How to use
Step1.Clone this repo  
Step2.Put all proto fils to ./proto/  
Step3.use`start.bat` or`node getcmdids_pancake.js`to run  
# Fork
Compared with the original, 
 - This fork fixed an issue where some of the grasscutter instructions were still executed after selecting pancake. 
 - PacketIds.json is generated when pancake mode is selected.
 - Modified the file name generated by `grasscutter` mode.
 - Added some content to the generated file.
 - You may still need to check `packetids.json` file to make some format changes.
