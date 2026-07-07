# dmg-01-reboot (Cheese Boy)

A fully modernized, retro-futuristic revive for the classic Game Boy DMG-01. This is a complete DIY project featuring a Raspberry Pi Zero, a vibrant full-color LCD screen, and working microSD cartridges—all in the iconic original shell.

---

## 🎮 What Is This?

`dmg-01-reboot` is an open-source hardware and software project that brings the beloved Game Boy into the modern era. It's designed for retro gaming enthusiasts, makers, smart-but-bored people, and anyone who loves a good weekend project.

This is **my first big project**, so I'm excited to share it and would love your feedback, builds, and recommendations!

---

## ✨ Features

- **Raspberry Pi Zero Powered** - Compact, powerful, and perfect for retro emulation
- **Full-Color LCD Screen** - Say goodbye to the monochrome dot matrix
- **Backlight** - For the late-night Goomba-stomping grinds
- **MicroSD Cartridges** - Load your favorite games from cartridge-style media
- **Original DMG-01 Shell** - Classic form factor with modern internals
- **RetroPie Compatible** - Runs RetroPie with custom hardware plugins for seamless integration
- **Fully Open-Source** - All design files and code included in this repository

---

## 🛠️ What You Need to Build

### Skills Required
- Basic soldering experience (through-hole)
- Surface mount soldering (SMT/SMD) experience
- Familiarity with Raspberry Pi setup

### Materials & Bill of Materials

This project consists of multiple PCBs, each with its own Bill of Materials (BOM). Check the relevant BOM file for each PCB you're building:

- **Main Board** - See `/hardware/main-board/BOM.md`
- **Display Board** - See `/hardware/display-board/BOM.md`
- **Cartridge Board** - See `/hardware/power-board/BOM.md`
- *(Add additional boards as your design takes shape)*

**Note:** BOMs are organized by PCB in the `/hardware` directory. Each folder contains:
- Schematic files
- PCB design files (Gerber format for ordering)
- Component BOM for that specific board

---

## 📦 Repository Structure

```
dmg-01-reboot/
├── hardware/           # PCB design files, schematics, and BOMs
│   ├── main-board/     # [Add your PCB folders here]
│   ├── display-board/
│   ├── power-board/
│   └── ...
├── software/           # RetroPie plugins and configuration
├── docs/              # Build guides and troubleshooting
├── assets/            # Images and diagrams
└── README.md          # This file
```

---

## 🚀 Quick Start

1. **Order PCBs** - Use the design files in `/hardware` to order from your favorite PCB manufacturer (Gerber files included)
2. **Gather Components** - Consult the BOM files and DigiKey for all required parts
3. **Solder the Board** - Assemble through-hole, SMT, and SMD components
4. **Set Up Raspberry Pi** - Flash RetroPie and install the custom hardware plugins from `/software`
5. **Assemble** - Fit everything into the Game Boy shell
6. **Load Games** - Add your favorite ROMs to the microSD cartridge
7. **Enjoy!** - Play retro games on modern hardware

For detailed build instructions, see `/docs/BUILD_GUIDE.md`.

---

## 💻 Software

The project runs **RetroPie** with custom control routing designed specifically for the dmg-01-reboot hardware. These plugins handle:
- LCD display integration
- Button mapping and input handling
- MicroSD cartridge detection and ROM loading

Installation and configuration instructions are included in this repo.

**small disclaimer**: this is not a package install. it will just be a guide for mapping with the retropie software. In fact, this is my first time using RetroPie or even doing DIY game mods apart from programming school calculators, so please give me some grace.  

---

## 📸 Share Your Build!

This is an open-source community project, and **I'd love to hear from you!** If you build one, please reach out:

📧 **Email me photos and recommendations** - Your feedback helps improve the design and helps other builders learn from real-world builds.

Whether it's a tip, a modification, a bug fix, or just pictures of your finished device—**all contributions are welcome and encouraged**. This is my first big project, so your input is invaluable.

---

## 🤝 Contributing

We welcome contributions! Here's how:

1. **Fork the repository**
2. **Make your changes** (hardware improvements, bug fixes, software enhancements)
3. **Test thoroughly**
4. **Submit a pull request** with a description of your changes
5. **Email me too!** - Include pictures or notes about what you changed

---

## 📋 Project Status

🚧 **In Active Development** - The design is still being refined. Check back for updates as the project matures.

Once the design is fully finalized, a detailed changelog and version history will be added.

---

## Troubleshooting

Having issues? Check `/docs/TROUBLESHOOTING.md` for common problems and solutions. If you find something not covered, please reach out!

---

## ⚠️ Disclaimer

This is a personal/hobby project built for educational and hobbyist purposes. Make sure you own the games/ROMs you're playing. Respect copyright laws in your jurisdiction.
I am not an electronics expert. I consider my self well-versed in electronics. keep in mind that I WAS BORN IN 2013; although I have worked with and taught myself the art of electronics since around 2018. I AM NOT, IN ANY WAY, RESPONSIBLE FOR ANY PHYSICHAL OR MENTAL HARM CAUSED BY MY PROJECT. YOU CHOSE TO BULD THE PROJECT. I AM JUST THE DESIGNER.

---

## 📄 License

This project is open-source. See the `LICENSE` file for details.

---

## Acknowledgments

Thanks to:
* Texas Instruments Datasheets (`https://www.ti.com/lit/ds/symlink/tps56339.pdf?ts=1783426660975`),
* Kamicane's super-dmg-01 repo for some motherboard footprints (`https://github.com/kamicane/Super-DMG-01`),
* The Raspberry Pi foundation, for providing the core of this project,
* And the Ezell-Turner Family for inspiration, encouragement, and an absolutely stunning Independence Day fireworks show!

  This project builds on your shoulders.

  I strongly encourage you to check out Vadis Turner's Mixed media art sculptures and support her work. Her site is at `https://vadisturner.com`. Your assistance in growing her community would mean a lot to me!
Thank you Clay Ezell for donating your childhood DMG-01, and my parents, who have been here for me to help me get through the hardest parts of my life.
What a long, strange trip it's been!

---

## 📧 Contact

Have questions, suggestions, or just want to share your build? **Reach out!**

Feel free to open an issue on GitHub or send me an email with your thoughts. This is a community project, and your feedback makes it better.

---

**Happy building, and enjoy your modernized Game Boy!** 
