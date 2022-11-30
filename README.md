# beep
Beep from Spkr MOBO!

### Dependencies

sudo apt install beep

sudo chmod 777 /dev/input/by-path/platform-pcspkr-event-spkr

sudo env -u SUDO_GID -u SUDO_COMMAND -u SUDO_USER -u SUDO_UID beep

beep
