# The Emporium of Digital Delights Showcase

Created to showcase projects developed during Prewired's 2021 Summer Hackathon, dubbed **The Emporium of Digital Delights** (EoDD). Developed using [Hugo](https://gohugo.io/) and based on the [Blist](https://github.com/apvarun/blist-hugo-theme) theme.

### Setup

These instructions assume you are using Ubuntu or similar Linux distribution. 

1. Install [Homebrew](https://brew.sh/)
2. Install [nvm](https://github.com/nvm-sh/nvm)
3. Use Homebrew to install Hugo: 

```
brew install hugo
```

4. Use nvm to install/update nodejs and npm:

```
nvm install node
```

5. Clone this repo and its submodules:

```
git clone --recurse-submodules git@github.com:HutchieV/eodd.git
```

6. Install node modules:

```
cd eodd
npm i
```

7. Launch the auto-updating server. By default, this is live at [http://localhost:1313/](http://localhost:1313/):

```
hugo serve
```

### Netlify

The file `netlify.toml` contains the basic configuration for deploying on Netlify.

### Emoji shortcodes

Useful reference: [link](https://www.webfx.com/tools/emoji-cheat-sheet/)