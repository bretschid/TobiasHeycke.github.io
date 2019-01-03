---
layout: default
---

# Installing a complete MiKTeX distribution (Windows)

If you are using the papaja package, life will be easier if you install a complete MiKTeX system. 
Even when you install missing packages on-the-fly (see [automatic package installation](https://miktex.org/howto/miktex-console)) I experienced problems (e.g., when knitting a document in journal style). 
I therefore reccomend installing the full MiKTeX system, even though it is quite large.
Here is a simple step by step guide:

### Download

- Go to the [MiKTeX Download page](https://miktex.org/download)
- Go to 'All downloads'
- Select the 'Net Installer' ([32 or 64 Bit depending on your system](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64)
- Download the file (named: 'setup' plus a version number)
- Run this file
- Accept the terms and conditions and continue
- Select Download MiKTeX and continue
- Now the important part: Select 'Complete MiKTeX' and continue
- Select your favorite download source and continue (make sure the source is not just D:/Downloads but D:/Downloads/MiKTeX, otherwise you will have thousands of individual files in your downloads folder)
- Select a downloads folder, remember the location, and continue
- Start the download and make yourself something to eat or spend time with your family (the download will take a while)
- Once the download has finished exit the download menu

### Installation

- To install the full MiKTeX system, go to the folder you downloaded the files to 
- You will find a couple  of thousand files there and you should open a setup (.exe) file within this folder (it will start with "setup" and then the version number .exe)
- Again accept the conditions and continue
- Select 'Complete MiKTeX' and continue
- Choose whether only you or everybody on a computer can use the installation and continue
- Select an installation path and continue 
- Select your preferred page size (A4 of course)
- You can also choose whether you want packages to be installed on the fly. If you create .tex files from RStudio it is advisable to select 'Yes' as the 'Ask me first' does not work from within RStudio
- Start the installation (Again, probably going to take a bit)
- Once the installation is finished you can continue and are asked on the next page if you want to check for updates. You can do that and continue
- You have now installed MiKTeX
- You can adjust settings by opening the 'MiKTeX Console' from your start menu






