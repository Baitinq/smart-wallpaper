# Smart-Wallpaper

A simple bash script that automatically changes your wallpaper depending on if its daytime or nighttime (helps your eyes).

## Getting Started

You can either clone the repository and run the script or if you are running Arch or derivatives get it from the AUR (https://aur.archlinux.org/packages/smart-wallpaper-git/).

### Dependencies

Required: redshift - determining if its day/night in your location.
          feh - setting the wallpaper.
          bash

Optional: gifsicle - animated wallpaper support

### Usage

Usage: smart-wallpaper [FLAG]\n
  Flags:\n
    [-d]: NEEDED   : daytime wallpaper file/folder\n
    [-n]: NEEDED   : nighttime wallpaper file/folder\n
    [-l]: OPTIONAL : manual location (lat:long), if not added geoclue gets the location (requires internet)\n
    [-h]: OPTIONAL : print help message

Example:
```
smart-wallpaper -d /home/user/Wallpapers/DayWallpaperFolder -n /home/user/Wallpapers/NightWallpaperFolder -l 0:0
```

## Contributing

Feel free to submit pull requests to clean up the code/adding new features. Thank you!


## Author

* **Baitinq** - *Whole script* - (https://github.com/Baitinq)

## License

This project is licensed under the GPL License.

## Acknowledgments

* Stackoverflow me like
