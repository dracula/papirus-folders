### [Papirus Folders](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme)

#### Install

1. Make sure You have [Papirus Icon Theme](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme) installed (preferably in `~/.local/share/icons`);
2. Also, check if you have the [Papirus Folders Script](https://github.com/PapirusDevelopmentTeam/papirus-folders) installed in your home via [this method](https://github.com/PapirusDevelopmentTeam/papirus-folders#install);
3. Clone this repository and change to the cloned directory:
   ```bash
   git clone https://github.com/dracula/papirus-folders
   cd papirus-folders
   ```
4. 🏃🏻 Run: `cp -r Icons/* ~/.local/share/icons/Papirus`, from the repo's directory if you have installed Papirus for the user;<br />
   If you have installed Papirus system-wide, run: `sudo cp -r Icons/* /usr/share/icons/Papirus`;
5. 🏃🏻 Run: `papirus-folders -lv` in the terminal to check whether the dracula-themed icon names are listed or not;
6. Now, you can set the folder icons you prefer using `papirus-folders` command (that you installed in _step 2_);<br />
   ✅ You can check the steps to use it [here](https://github.com/PapirusDevelopmentTeam/papirus-folders#script-usage);<br />
   👇🏻 Example: <br />
   `papirus-folders -C dracula-default --theme Papirus`
7. Boom! It's working ✨
