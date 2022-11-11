# WSL Cheat Sheet

## General Information
* Only short form is noted.

### List installed distributions
wsl -l

### List installed distributions, running state and wsl version
wsl -l -v

### Run specific distribution
wsl -d <distro_name>

### Terminate a specific distro
wsl -t <distro_name>

### Shutdown all distros
wsl -t --all

### Set distro as default
wsl -s <distro_name>

### Export running distro as image
wsl --export <distro_name> <export_path/file_name.tar>

### Import image as distro
wsl --import <distro_name> <path_to_file/filename.tar> --version [1|2]

### Unregister (delete) a distro
wsl --unregister <distro_name>
