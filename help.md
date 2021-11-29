# Programs Used

- Terminal: Alacritty
- System Manager: htop
- Launcher: dmenu
- Audio: alsa, pulceaudio, pamixer
- Music: mpd, mpc, ncmpcpp
- Browser: Brave
- Editor: nvim
- Wallpaper: nitrogen
- Mail: neomutt
- FileManager: ranger
- Screenshot: scrot
- Lock Screen: slock
- Network Manager: nmtui
- TaskSwitcher: skippy-xd
- Screenshot and Annoate: flameshot

# KeyBindings

## Layout

| Symbol | Layout       | Key     | Discription                                 |
| ------ | ------------ | ------- | ------------------------------------------- |
| []=    | tile         | t       | Default: Master on left, slaves on right    |
| TTT    | bstack       | shift t | Master on top, slaves on bottom             |
| [@]    | spiral       | y       | Fibonacci spiral                            |
| [\\]   | dwindle      | shift y | Decreasing in size right and leftward       |
| [D]    | deck         | u       | Master on left, slaves in monocle-like mode |
| [M]    | monocle      | shift u | All windows on top of eachother             |
| |M|    | centeremaster| i       | Master in middle, slaves on sides           |
| >M>    | centerefloat | shift i | Same but master floats                      |
| ><>>   | NULL         | shift f | no layout function means floating behavior  |

## Window and Navigation

- j : Focus to Next Window
- k : Focus to Previous Window
- v : Focus to Master
- h : resize window to left
- l : resize window to right
- number : change tag to that number
- shift number : move active window to that number tag
- tab : toggle between recent tag
- right : view next active tag
- left : view previous active tag
- shift right : move active window to next tag
- shift left : move active window to previous tag
- q : kill window
- shift q : logout

- o : increase number of master windows
- shift o : decrease number of master windows
- s : toggle sticky window
- f : fullscreen
- b : togglebar
- g : shift to prvious view
- shift g : move window to previous view
- semicolon(;) : shift to prvious view
- shift semicolon(;) : move window to previous view

## Useless Gaps

- a : toggle useless gaps
- shift a : default gaps
- z : increase gaps
- x : decrease gaps

## Music

- minus(-) : decrese 5 volume
- shift minus(-) : decrese 15 volume
- plus(+) : increase 5 volume
- shift plus(+) : increase 15 volume
- p : mpc toggle
- [ : seek 10 sec back
- ] : seek 10 sec forward
- shift [ : seek 60 sec back
- shift ] : seek 60 sec forward
- ctrl shift m : mute pulseaudio

## Launch

- return : Terminal
- c : Browser
- r : Ranger File Manager
- e : GUI File Manager
- shift r : System Manager
- w : change wallpaper
- shift w : network manager
- shift e : Email
- d : dmenu
- shift space : passmenu
- m : window overview
- shift m : music player

## Function Keys

- f1 : help
- f3 : display select
- f4 : pulsemixer
- f6 : torwrap
- f7 : td-toggle
- f8 : dmenumount
- f9 : dmenuunmount
- f11 : WebCamera
- f12 : input methods

