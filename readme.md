# Creating a new Windows 2012 Hyper-V image using Vagrant

## Quick start

### Setup
- Copy `S:\Development\Vagrant-Boxes\Hyper-V\` to a directory on your machine (`C:\VMs\` is the convention)

- Copy S:\Development\Vagrant-Boxes\Installers to your machine (`C:\VMs` is the convention)

- Go to Hyper-V manager, on the right hand side go to "Virtual Switch Manager"

- Create an External switch, call it whatever you like (I like "mega switch"), select your ethernet adapter in the drop down

- Open a command prompt *as Administrator* from the directory from `C:\VMs\Hyper-V\dev-wsx`

- Go back to the command prompt and type `vagrant up`

- When the machine starts use a product key from MSDN for Windows Server 2012 r2 with update, or skip this and do it later

- On the Hyper-V image, clone the Chef repo (`C:\Code` is the convention)

- Open powershell, CD to `c:\Code\Chef\src\Dev-machine` and run JobSeeker-Setup.ps1

Job Done!
