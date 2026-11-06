# HP ZBook 15 G6 EasyEffects Preset

An EasyEffects preset for the Bang & Olufsen speakers on the HP ZBook 15 G6 utilizing the Realtek ALC285 codec, for necessary speaker amplification and balancing. 

While the HP Clear Sound Amp module is set to be powered on ([Source](https://lkml.iu.edu/hypermail/linux/kernel/2112.1/03834.html)), its amplification and balancing effects are not present, leading to a very flat and empty speaker. This preset mimicks the missing feature.

# Installation Guide

1. For the easiest setup, download the installer **[here!](https://github.com/Purgenta889/easyeffects_hpzbook15g6/releases)** 

2. Next, in your file manager, right click on the `.sh` file, and select "Properties".

3. In the newly opened menu, toggle "Execute as Program" or a similarly named option, depending on your file manager. For example, on systems running GNOME, such as Zorin OS and Fedora Workstation:

<p align="center">
  <img src="https://github.com/user-attachments/assets/0b332431-7a8b-4a2f-9812-a29df67e01a5" alt="GNOME File Properties" width="369" />
</p>

On systems running KDE, such as CachyOS, Bazzite, and Kubuntu:

<p align="center">
  <img src="https://github.com/user-attachments/assets/4f814cfb-c6d9-41d7-838b-ce7697029982" alt="KDE File Properties" width="369" />
</p>

4. Next, double click on the `.sh` file to run it.

<p align="center">
  <img src="https://github.com/user-attachments/assets/527d75a4-e146-4ff9-82b4-f997559678da" alt="Installer Prompt" width="369" />
</p>

5. Your install location may look different based on how you installed EasyEffects. Click install.

6. If EasyEffects was open, restart it.

7. Select the preset.

### Alternative Installation (CLI)

If you prefer using the terminal, download the CLI installer **[here!](https://github.com/Purgenta889/easyeffects_hpzbook15g6/releases)** 

#### CLI Installation Guide

1. Open a terminal in the location of where you downloaded it (typically `~/Downloads`) or `cd` there.

2. Run `sh ./install-easyeffects-preset-cli`.

3. This window will show, press `y` on your keyboard and then Enter:

<p align="center">
  <img src="https://github.com/user-attachments/assets/d9c213e7-e103-48bb-9f8a-6d83ceca7d47" alt="CLI Confirmation Prompt" width="650" />
</p>

4. If EasyEffects was open, restart it.

5. Select your preset.

## Troubleshooting

### The GUI Installer Won't Launch

You may not have the necessary GUI packages installed. This likely applies to you if you are using Arch Linux or a derivative. Please install one of the following as system packages:

- `zenity`

- `kdialog`

Afterwards, run the program again.
