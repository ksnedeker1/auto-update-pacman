# auto-update-pacman
Simple shell script for semi-automated system updates (pacman -Syu). Checks the Arch Linux news page, alerting the user and exiting before updating if there are any new news posts since the last time the system was updated. This helps lower the chance of breakages stemming from users applying system updates without checking the news, while also promoting an up-to-date environment.

## Setup
Move **auto-update-pacman** to ```/usr/local/bin``` and make executable with ```chmod +x /usr/local/bin/auto-update-pacman```.

Add the contents of **example-automation** to your ```~/.bashrc```, ```~/.zshrc``` or equivalent shell startup file with ```cat example-automation >> ~/.zshrc```, substituting paths appropriately.
