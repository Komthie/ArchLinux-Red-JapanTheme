# ArchLinux-Red-JapanTheme

![image](https://github.com/Komthie/ArchLinux-Red-JapanTheme/assets/95933637/694ab4f9-938f-4cf9-a76d-420f986fa667)
![image](https://github.com/Komthie/ArchLinux-Red-JapanTheme/assets/95933637/5eb59a43-dee9-41c6-ba98-58967016eaa3)

# Foreground / block screen:
![image](https://github.com/Komthie/ArchLinux-Red-JapanTheme/assets/95933637/41163999-db88-4afb-9089-7f67e004af0a)



Elements:

    Color palette:
        Red: Primary color, symbolizing energy, passion, and good luck.
        White: Secondary color, representing purity, simplicity, and peace.
        Black: Tertiary color, accentuating the depth and contrast of the theme.
    Icons:
        Minimalist design with traditional Japanese elements, such as cherry blossoms, fans, and Kanji symbols.
        Colors from the red, white, and black palette for visual harmony.
    Cursor:
        Traditional Japanese style, like a calligraphy brush or a Katana sword.
        Colors from the palette to complement the theme.
    Lockscreen:
        Background image with stunning Japanese landscapes, such as Mount Fuji or cherry blossoms in bloom.
        Minimalist clock with an elegant Japanese font.
    Top bar:
        Transparent design to highlight the background image.
        Simple and elegant icons for applications and menus.
    Applications:
        Customized GTK and Qt themes to match the color palette and overall style of the theme.
        Japanese fonts for an authentic experience.
        
## Installation Neofetch:

      
    Debian/Ubuntu: sudo apt install neofetch
    Fedora: sudo dnf install neofetch
    Arch Linux: sudo pacman -S neofetch
    openSUSE: sudo zypper install neofetch
    To configure Neofetch to tengu mask ASCII

## ASCII Tengu Mask:
    
    copy the ascii tengu mask from main ascii mask
    or here https://emojicombos.com/oni-mask
    and paste in your directory with nano or vim
    example: </home/user/ascii/oni_mask.ascii
    paste ascii

    
## Neofetch configure in .zsrch file:

    cd /home/user/
    sudo vim/or nano/ .zshrc (or bashrc)
    paste in your .zshrc file:
    neofetch --source /home/user/your_directory_with_ascii_art
  ![image](https://github.com/Komthie/ArchLinux-Red-JapanTheme/assets/95933637/981e0d6d-db72-46ae-bc62-960da1244eb6)

      

## Backgrounds Wallpapers Red Japan Links:

    https://www.uhdpaper.com/2024/05/anime-girl-with-tattoo-4k-8k-7353a.html
    https://www.uhdpaper.com/2024/06/anime-girl-demon-horn-tattoo-4k-8k-6160j.html
    https://img.uhdpaper.com/wallpaper/anime-girl-katana-tattoo-228@3@a-thumb.jpg?dl
    https://www.uhdpaper.com/2024/04/anime-girl-katana-tattoo-4k-8k-2283a.html
    
## installing sww and img to change the background:

    Archlinux
    sudo pacman -S swww
    
    Debian/Ubuntu:
    sudo apt install swww
        
    Fedora:
    sudo dnf install swww

    openSUSE: 
    sudo zypper install swww

## Installing wal on Arch Linux for the colors in terminal with wallpaper:

    Embrace Simplicity: Open your terminal and execute 
    the following command to effortlessly install wal:

    sudo pacman -S wal-terminal-colors
    
    Configuration is Key: Create a directory to store your wallpapers and terminal color schemes:
    
    mkdir ~/.config/wal
    Wallpaper Wonderland: 
    
    Navigate to the newly created directory and download some wallpapers to use with wal:
    cd ~/.config/wal
    wget https://github.com/dylanaraps/wal/archive/master.tar.gz
    tar -xf master.tar.gz
    mv wal-master/* .
    rm -rf wal-master
    
    Unleash the Magic: Set a wallpaper and update your terminal 
    colors based on the wallpaper's colors using this command:
    wal -i [path_to_wallpaper_file]
    Customization Galore:
    Explore a world of options and customizations for wal by running the command:
    
    wal --help


## Installing wal on Other Linux Distros:

    1. Debian/Ubuntu:
    sudo apt install wal

    
    2. Fedora:
    sudo dnf install wal
        
    3. openSUSE:
    sudo zypper install wal
        
    4. Gentoo:
    emerge --ask app-misc/wal
        
    5. Building from Source:
    git clone https://github.com/dylanaraps/wal.git
    cd wal
    make install
    
## Paste the Command line for swww and wal in your .zshrc or others bash's:

    swww -i /home/user/your_directory_japan_image_here/japanarch.png && wal -i /home/user/your-directory-japan-here/japanarch.png

## Mouse RedJapanTHeme Install:
![image](https://github.com/Komthie/ArchLinux-Red-JapanTheme/assets/95933637/dca1d9c0-1f24-4e45-a917-4e1616b407d5)


      http://www.rw-designer.com/cursor-set/redset
      install e move for the ./~icons directory

      Set the cursor theme:

      After choosing a red cursor theme, you can set it using your desktop environment's settings
      or a dedicated tool. The specific steps may vary depending on your desktop environment, 
      but you can usually find the cursor theme settings 
      in the "Appearance" or "Personalization" section.

## Method 2: Manually Installing a Cursor Theme

    Download the cursor theme:
    Find a red cursor theme you like and download it. 
    You can find cursor themes on websites like https://developer.mozilla.org/en-US/docs/Web/API/IDBObjectStore/
    openCursor or https://www.gnome-look.org/browse?cat=107&ord=latest.

    Extract the cursor theme:
    Once the cursor theme is downloaded, 
    extract it to the appropriate directory. 
    The location of this directory may vary depending on your distribution, 
    but it is typically something like ~/.icons or /usr/share/icons.

    Set the cursor theme:
    Follow the instructions in Method 1 to set the cursor theme.
    The red cursor theme you downloaded should now be available as an option.

## Install the kanagawa theme:
![image](https://github.com/Komthie/ArchLinux-Red-JapanTheme/assets/95933637/70389696-c44a-4f15-8eeb-4ba3aa7c062c)
![image](https://github.com/Komthie/ArchLinux-Red-JapanTheme/assets/95933637/854069b9-1bdf-4d24-9e87-0be53292f0a3)

    https://github.com/Fausto-Korpsvart/Kanagawa-GKT-Theme

    2. Extract the Icon Theme:

    Once the icon theme package is downloaded, extract it to the appropriate directory. 
    The usual location for icon themes is ~/.icons for user-specific themes and 
    /usr/share/icons for system-wide themes.
    
    For Arch Linux:
    If you're using Arch Linux, 
    you might need to install the hicolor-icon-theme package to ensure compatibility
    with various applications. Use the following command:
  
    sudo pacman -S hicolor-icon-theme
        
    3. Set the Icon Theme:
    The method for setting the icon theme depends on your desktop environment. Here's a general approach:

    GNOME:
        Go to "Settings" and navigate to the "Appearance" section.
        Under "Icons," select the desired icon theme from the dropdown menu.

    KDE Plasma:
        Open "System Settings" and go to "Appearance."
        Under "Global Theme," switch to the "Icons" tab.
        Choose the icon theme you want from the list.

    XFCE:
        Right-click on the desktop and select "Preferences."
        Choose "Appearance" and then "Icons."
        Select the icon theme you downloaded from the list.

    4. Verify the Icon Theme:
      
      After setting the icon theme,
      restart your applications or log out and log back in to ensure the changes take effect.
      You should now see the new icons applied throughout your system.

## Hashtags:
      #ArchLinux #Theme #Oriental #Japanese #Red #White #Black #Minimalism #Elegance #JapaneseCulture #Kanji #Landscapes #MountFuji #CherryBlossoms #Calligraphy #Tradition #Symbolism

## Acknowledgments:

I thank everyone who contributed to this project and I hope you enjoy the theme!
This customized Arch Linux theme transports your desktop to a mystical oriental environment, inspired by the timeless beauty of Japanese culture. The red, white, and black color palette creates a striking contrast, evoking the strength, purity, and elegance of Japanese tradition.
