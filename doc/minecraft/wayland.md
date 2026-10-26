# Speedrunning on Wayland

- Wayland, as mentioned earlier, is newer and more up-to-date than X11. We recommend you first try speedrunning on Wayland, and [switch to X11](x11.html) if you face major problems, such as poor FPS when using waywall.
- On Fedora KDE Plasma, Wayland is the default backend.
- Setup [waywall](./wayland/waywall.html) for Ninjabrain Bot support, window resizing, key remapping, magnifiers, and many other useful speedrunning utilities.
- After setting up waywall:
  - see [Boat Eye on Wayland](./wayland/boat-eye.html) to setup pixel perfect eye measuring (boat eye) both for new players and those who already had boat eye setup on Windows.
  - see [Keymap Rebinds using waywall](./wayland/rebinding.html) for setting up rebinds for search crafting.

# Installer Script
> **Always be very careful running the scripts of the internet, only run the script that you can trust**

Below is the automated installation script created by [snaw](https://github.com/lemonsnaw).
It does following:
- Download and setup default JDK to avoid issue related to headless JDK
- Download and install Prism launcher(flatpak prisms backup is taken at runtime)
- Downloads and install waywall
- Downloads Gores Generic Config sets it up for waywall
- Configures your minecraft instance to use waywall ( wrapper and glfw setup
- Setup Ninjabrain bot for boateye (godsens,greenboat,std deviation etc).
( doesnt set sensitivies in waywall , you have to do it manually. Please check guide here https://its-saanvi.github.io/linux-mcsr/minecraft/wayland/boat-eye.html)
- Optionally, can setup plugwaywall + plugins and dragclicking support at any point later in time.


Check how to run and supported os on their page:
**https://github.com/lemonsnaw/snaws-waywall-installer**

