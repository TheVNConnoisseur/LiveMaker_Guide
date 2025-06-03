# LiveMaker_Guide
Repository of official tools and information for LiveMaker visual novel engine (created by [Humanbalance](https://humanbalance.net/)).

### What tools do we have at our disposal?
Since this repository will focus soly on official tools, we only have two, [LiveMaker](https://livemaker.net/) and [GraphicsGale](https://graphicsgale.com/us/).

- **LiveMaker:** the SDK tool. There are three main revisions of the engine, version 1, 2 and 3. Exclusive to the 1st first version, it was offered a Pro tier, but it only meant that the product generated with the Free version couldn't generate more than a certain amount of money.
- **GraphicsGale:** the official creator of .GAL images. It is simply an image editor, and a surprisingly complex one for what it is. While it can generate images for different formats, it is advisable to use another program for actual image editing, and leave this one strictly for .GAL creation.

### How can .GAL images be created?
At the moment, there are 2 officially supported ways to create them:
- **Adobe Photoshop Plugin:** there is a 32-bit only (Adobe Photoshop CC 2018 is the most modern version for Windows that has a 32-bit build) plugin that can create and open files without a problem. If you decide to open a version 2 of a .gal file with version 1 of the tool, the program will crash. When saving an image, it will ask for what kind of compression to use: Normal, No compression, or custom (by selecting a quality factor).
- **GraphicsGale:** the official tool for the creation of .GAL images. The program is still supported to this day. Sadly, for version 1 of .GAL images, the free tier of this program did not receive the latest update, hence why versions 1.93.25 (free) and 1.93.26 (pro with 30 days trial) are both offered.

There is also a DLL library meant to offer support of creation and management of .GAL files in external applications, alongside a C# implementation done by a Spanish developer (endorsed officially by Humanbalance).

### Selecting the correct version for everything
- **LiveMaker:** if you need to work with a pre-existing game, the main executable will tell you the engine revision used.
- **.GAL:** version 1 of LiveMaker engine tends to use version 1 of .GAL images, while the other 2 used version 2. In case of doubt, check any image of the game you wanna tinker with and check the extension that [GarBro](https://github.com/crskycode/GARbro/) says. If it mentions [GAL], it is version 1, and if it says [GAL/X200], it is version 2.
