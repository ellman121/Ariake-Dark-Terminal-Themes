# Ariake-Dark-Windows-Terminal-Theme

Based on the largely popular [Ariake Dark Atom Theme](https://github.com/pathtrk/ariake-dark-syntax) and the [VS Code variant](https://github.com/a-wart/ariake-dark).  This version is not a perfect recreation, but it's close enough for me to enjoy in my terminal(s).  PRs to improve are welcome.

## Installation

1. Open Windows Terminal
2. Click the Down Arrow and open settings (`ctrl + ,` by default)
3. Copy / Paste the JSON object into `schemes`

```
 "schemes": [
     {
         "name": "Ariake-Dark",
         "cursorColor": "#E89CFC",

         "black" : "#000000",
         "red" : "#993d3d",
         "green" : "#78b378",
         "yellow" : "#999900",
         "blue" : "#7bb1e5",
         "purple" : "#e89cfc",
         "cyan" : "#00a6b2",
         "white" : "#bfbfbf",
         "brightBlack" : "#666666",
         "brightRed" : "#cc5252",
         "brightGreen" : "#91d991",
         "brightYellow" : "#e5e500",
         "brightBlue" : "#7fdfff",
         "brightPurple" : "#ff0cff",
         "brightCyan" : "#00e5e5",
         "brightWhite" : "#e5e5e5"
     }
 ],
```

4. Under `defaults`, add the key `colorScheme` with the value `"Ariake-Dark"`

```
"defaults":
{
    // Put settings here that you want to apply to all profiles.
    "colorScheme": "Ariake-Dark",
    
    "... Other settings ...": "..."
},
```

5. Save and enjoy
