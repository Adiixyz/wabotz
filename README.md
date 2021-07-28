# WHATSAPP BOT
# SC BY 
* [`ariffb25`](https://github.com/ariffb25)

# Installation ( Termux )
```cmd
> pkg install git
> pkg install bash
> git clone https://github.com/Adiixyz/wabotz
> cd wabotz
> bash install.sh
```
_Note_ : Use `apt` if `pkg` doesn't work

# Installation ( Windows, VPS, RDP )

* Download And Install Git [`Click Here`](https://git-scm.com/downloads)
* Download And Install NodeJS [`Click Here`](https://nodejs.org/en/download)
* Download And Install FFmpeg [`Click Here`](https://ffmpeg.org/download.html) (**Don't Forget Add FFmpeg to PATH enviroment variables**)
* Download And Install ImageMagick [`Click Here`](https://imagemagick.org/script/download.php)

```cmd
> git clone https://github.com/Adiixyz/wabotz
> cd wabotz
> npm i
```

# Run
```cmd
> node index.js
```

# Edit required value at `config.js`
```js
global.owner = [] 
global.mods = [] 
global.prems = [] 

// Sticker WM
global.packname = 'Whatsapp Bot'
global.author = 'wabotz'

global.multiplier = 69 // The higher, The harder levelup
```
# Edit this
`global.owner` Put your owner number
`global.mods` Moderator number
`global.prems` Put number for premium
`global.packname` Your packname for sticker
`global.author` Your author for sticker
`global.multiplier` When higher, Hardest to level up

# Thanks To
* [`Ariffb`](https://github.com/ariffb25)
