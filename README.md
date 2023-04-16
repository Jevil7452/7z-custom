# 7z-custom
 7-Zip source code with custom file size split presets. Created for personal use

# What's different from normal 7-Zip?
 There are new file size split presets added:
 
 8MB - Discord's old file limit. Use if your client doesn't support 25MB free uploads
 
 25MB - Discord's free file size limit
 
 50MB - Discord Nitro Basic's file size limit
 
 500MB - Discord Nitro's file size limit
 
# Building
 You will need to have Visual Studio C++ workflow installed.
 
 Open a x64 Native Tools Command Prompt for VS (or x86, if you need an x86 build)
 
 Go to `<source code's root folder path>\CPP\7zip`
 
 Type `nmake`
 
 After it's done, go to `<source code's root folder path>\CPP\7zip\UI\GUI\x64`, find `7zG.exe`, and replace the copy in your 7-Zip install with the one you compiled

# Original code
 The original author of 7-Zip is Igor Pavlov
 
 The original source code can be downloaded from https://www.7-zip.org/a/7z2201-src.7z
