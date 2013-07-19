# Byobu Smarter Status
 
Intelligent status bar modules for the Byobu text based window manager.

More information on Byobu is available at: [http://byobu.co/](http://byobu.co/)

## Purpose
 
Derived primarily from existing modules, these are capable of displaying
additional details and are highly configurable. Most modules also feature
dynamic coloring based on user-defined notice/warning conditions.

## Screenshots

Default config:
![Byobu Smarter Status default config screenshot](/screenshots/bss-screenshot-v01-default.png?raw=true "default config")

"semipro" sample config:
![Byobu Smarter Status semipro config screenshot](/screenshots/bss-screenshot-v01-semipro.png?raw=true "semipro config")

"minimal" sample config:
![Byobu Smarter Status minimal config screenshot](/screenshots/bss-screenshot-v01-minimal.png?raw=true "minimal config")

## Getting Started
 
### Prerequisites
 
A functioning install of Byobu, which is available for most *nix based systems.

### Installing
 
Typical instructions for a single user:

1.   Install and launch Byobu at least once.
2.   Copy the files from the project's .byobu/bin folder to your ~/.byobu/bin  
folder (create the folder if it doesn't exist).
3.   Make the copied files executable (chmod +x ~/.byobu/bin/*).
4.   Edit your ~/.byobu/status file to include one or more of the project's 
modules. See the project's .byobu/status.sample* files for examples.
5.   Optionally, edit the bss_config file that you copied to your ~/.byobu/bin
folder. See the project's .byobu/bss_config.sample* files for examples.

You could also install these modules in a common location that is accessible 
to all users and configure the default Byobu status files to use them. See 
the Byobu web site or man pages for more info.

## Copyright and License

Copyright 2013 Kristoffer Smith

Licensed under GPLv3 to maintain compatibility with the current version of 
Byobu.

[http://www.gnu.org/licenses/gpl-3.0.txt](http://www.gnu.org/licenses/gpl-3.0.txt)

## Contributing

Pull requests are welcome! Please contact me if you'd like to do a major re-work 
or extension of the project.

[https://github.com/theksmith/Byobu-Smarter-Status](https://github.com/theksmith/Byobu-Smarter-Status)

## Credits

### Authors

+	Kristoffer Smith ([http://theksmith.com/](http://theksmith.com/))

### Contributors

+	None yet

### Acknowledgments

+	Some modules contain code inspired by or sourced from scripts 
included in the Byobu application.