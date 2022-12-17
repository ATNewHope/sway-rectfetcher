# Sway-rectfetcher: A simple bash script fetch rect info using swaymsg

 This bash script could get the rect (i.e. absolute coordinates and size) info of the window with specified app_id (the first argument) in SwayWM.

 If multiple window matches, the focused window will be selected.
 If no one is focused, the first one will be selected.

 Remove every '#' before "$pecho" in the script file to get verbose output.

## Requirements
Window Manager: sway
Dependicies: swaymsg, jshon

## Usage
```bash
 $ sway-rectfetcher <app_id>
```

## Output format
```bash
 <x> <y> <width> <height>
```

## Example
```bash
$ sway-rectfetcher emacs
1080 1546 1800 374
```
