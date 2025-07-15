

# 🌸 vanilla – a hyprland rice

a moody, minimal hyprland setup inspired by the vanilla flower.  
soft, cinematic, and peaceful—built for quiet nights and clean screens.

> originally posted as [absolute cinema](https://www.reddit.com/r/unixporn/comments/1lzvi2j/hyprland_absolute_cinema/) on r/unixporn  
> shared because people asked 💜

check the friggin reddit boi
---

## 🖥️ features
```plaintext
- frosted blur via Hyprland
- minimal waybar with nerd font icons
- soft purple accenting (`#ccc2ff`)
- **rofi themed to match** (window blur + styled menu)
- clean kitty terminal config
- light config, heavy vibe
```
---

## 🔧 dependencies
```
built on Arch. install these with `pacman` or `yay`.
```
### required
```bash
hyprland
hyprpaper
waybar
rofi
kitty
zsh
ttf-nerd-fonts-symbols
````

### optional (recommended)

```bash
playerctl
pamixer
brightnessctl
spicetify-cli
powerlevel10k
```

---

## 📂 what’s inside

```plaintext
.config/
├── hypr        # hyprland config (blur, binds, etc.)
├── waybar      # bar layout + style
├── hyprpaper   # wallpaper
├── kitty       # terminal colors
└── fastfetch  # we all know what this is
```

---

## 🚀 setup

### 1. clone this repo

```bash
git clone https://github.com/yourname/vanilla
```

### 2. move configs into place

```bash
cd vanilla
cp -r .config/* ~/.config/
```

### 3. reload hyprland

```bash
hyprctl reload
```

> ⚠️ this replaces existing configs in `~/.config`. back them up first if you care.

---

## 💬 notes

* wallpaper not included—use a soft dark floral or grainy film photo
* rofi theme includes transparency + accent colors to match the vibe
* waybar icons rely on nerd fonts
* spicetify may need tweaking based on your Spotify version
* zsh prompt uses powerlevel10k (optional)

---

## 🙏 credits

* made with love, 4AM energy, and flower symbolism
* thank you to everyone who asked me to post this
* fork it, remix it, do what you want. vibes are free.

---

## ⭐ support

drop a ⭐ if you liked it
tag me if you remix it — i wanna see your flavor of **vanilla** 🌸

```
