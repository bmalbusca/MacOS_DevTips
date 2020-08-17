# Fix MacOS "no sound" problem
### Step 1 - Factory default settings
- Select "44100 HZ” and “2ch – 16 bit Integer”  

- In the pop-up box, enter ``~/Library/Preferences`` then click Go.
Scroll down and find ``com.apple.bluetooth.plist``.
Drag it to the Trash Folder and then turn off Bluetooth.  [url_source](https://www.ikream.com/how-to-fix-sound-problems-on-your-mac-running-macos-mojave-32751)


### Step 2 - Reset The Core Audio
- Use te terminal : ``sudo killall coreaudiod``

### Step 3 - Restart your computer

# Install OpenMP
1. ``brew install gcc@9`` - Just install an earlier version than gcc7
2. ``brew install libomp`` -  Install the library using brew
3. ``gcc-9 -o test  omp.c -fopenmp`` - Example of a compilation command

> **Note**
> installing MPI is more simpler: ``brew install openmpi``
>
> Compiling example: ``mpirun -np 2 <file>``
