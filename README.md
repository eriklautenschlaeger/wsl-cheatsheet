# Windows Subsystem for Linux

## Install WSL
1. `wsl --install -d <distro_name>`
   1. Install application 'Terminal' from Windows Store
   2. Enable the optional WSL and Virtual Machine Platform components
   3. Download and install the latest Linux kernel
   4. Set WSL 2 as the default
   5. Install Distro <distro_name>

## Cheat Sheet
### List installed distributions
`wsl -l`

### List online available distributions
`wsl -l --online`

### List installed distributions, running state and wsl version
`wsl -l -v`

### Run specific distribution
`wsl -d <distro_name>`

### Terminate a specific distro
`wsl -t <distro_name>`

### Shutdown all distros
`wsl -t --all`

### Set distro as default
`wsl -s <distro_name>`

### Export running distro as image
`wsl --export <distro_name> <export_path/file_name.tar>`

### Import image as distro
`wsl --import <distro_name> <path_to_file/filename.tar> --version [1|2]`

### Unregister (delete) a distro
`wsl --unregister <distro_name>`
