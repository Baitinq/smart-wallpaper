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

Usage: smart-wallpaper [FLAG]<br />
  Flags:<br />
    [-d]: NEEDED   : daytime wallpaper file/folder<br />
    [-n]: NEEDED   : nighttime wallpaper file/folder<br />
    [-l]: OPTIONAL : manual location (lat:long), if not added geoclue gets the location (requires internet)<br />
    [-t]: OPTIONAL : set the time period (seconds) for the script to check if it is day or night<br />
    [-r]: OPTIONAL : changes the wallpaper every day/night iteration<br />
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
