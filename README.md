# nnn-file-manager-wrapper
A wrapper around https://github.com/jarun/nnn to make it start with key bindings and allow it to be used as default file manager, while still allowing PLUGINS.

Install nnn using your package managers or directly from: https://github.com/jarun/nnn

Install https://github.com/mwh/dragon to allow drag and drop

- Clone this script with the other plugins
- git clone https://github.com/Sayyiditow/nnn-file-manager-wrapper.git
- cd nnn-wrapper
- chmod +x *
- make a link: 
- sudo ln -s /bin/nnnfm nnnfm
- sudo ln -s /bin/zip_this_file zip_this_file
- sudo ln -s /bin/imgur-upload imgur-upload

Add nnnfm to keyboard shortcuts or preferred applications to use as default file manager.

Features while in nnn:
1. Drag and drop files use ;d.
2. Make files executable using ;x
3. Upload images to imgur using ;i
4. Zip files using ;z
5. Unzip files using ;u
6. Execute scripts using ;s
