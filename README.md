Bootstrap laptop scripts
========================

0. Install Sublime Text 3 and all dependencies:
	- Package Control (Search Google and follow instructions for Sublime Text 3)
	- Emmmet (cmd + shift + P)
	- Theme SpaceGrey and update your personal config file with the theme line (Sublime Text > Preference > Settings - User):

```
"theme": "Spacegray.sublime-theme",
"color_scheme": "Packages/Theme - Spacegray/base16-ocean.dark.tmTheme"
```

1. Install a C compiler installing xcode tools and agree terms (if proceed). Open Terminal an write:

```
xcode-select --install
```

2. Generate SSH Keys and add them to github:

```
https://help.github.com/articles/generating-ssh-keys/
```

3. Create a ```work``` folder and go inside:

```
cd ~
mkdir work
cd work
mkdir personal
cd personal
```

4. Clone this repo to your machine:

```
git clone git@github.com:gemaderus/bootstrap.git
```

5. Enter to ```bootstrap``` folder and  run this in Terminal:

```
./laptop.sh
```

5. Install your dotfiles from your github repo