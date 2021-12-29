

# **Install Instructions**

Make sure you have installed Node.js into the VisionFive Fedora system. For instructions, refer to [Wiki](https://wiki.rvspace.org/en/Product/VisionFive/ApplicationNotes/V8_Demo).

The following are the command lines for using the `visionfive_chocolate-doom.tar.gz`  package:

1. Download the visionfive_chocolate-doom.tar.gz to  `/home/<user>/`, and execute:

   ```
   $ sudo dnf install SDL2-devel SDL2_mixer-devel SDL2_net-devel
   $ cd ~
   $ tar xvzf  visionfive_chocolate-doom.tar.gz
   $ cd chocolate-doom
   $ mkdir -p ~/.local/share/chocolate-doom && cp *.cfg ~/.local/share/chocolate-doom/.
   ```

2. Execute the following to run the official standard doom (shared software):

   ```
   $ ./chocolate-doom -iwad wads/doom1.wad
   ```

3. Play home-made doom games (open source BSD license) by executing:

   ```
   $ ./chocolate-doom -iwad wads/freedoom1.wad
   $ ./chocolate-doom -iwad wads/freedoom2.wad
   ```

   

# **Keyboard and Mouse Controls**



ENTER – Menu confirmation
- A – Left
- D – Right
- W – Move forward
- D – Move backward
- Shift+Direction - Run
- Space bar – Use (open)
- Mouse – Turn Left/Right
- Mouse Left – Shoot

Weapons
- 1 – Bare Hands
- 2 - Weapon1
- 3 - Weapon2
- 4 - Weapon3
- 5 - Weapon4
- 6 - Weapon5
- 7 - Weapon6
