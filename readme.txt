
--- msys_setup

- this is a set of scripts that setup an MSYS/MinGW environment on Windows and
  allows to compile libvirt and related libraries and tools



--- Is this what you're looking for?

- if you want a prebuilt Windows installer for libvirt, rather than compiling
  from source yourself, take a look at http://libvirt.org/windows.html

- that installer is for a quite old version by now and it includes 32-bit
  binaries only. more recent libvirt binaries for 32-bit and 64-bit are part
  of the the virt-viewer installer for Windows that can be downloaded from
  http://spice-space.org/download.html



-- General MSYS/MinGW environment setup

- download wget.exe from http://users.ugent.be/~bpuype/wget/ and put it in
  the same directory as msys_setup.bat

- run msys_setup.bat to download and setup an MSYS/MinGW environment

  you'll see automated Windows Installer popups for 7zip and Python. the
  script is not actually installing something to your system, it just unpacks
  both into subdirectories for later use.

  when you have UAC enabled (Windows Vista and Windows 7) then Windows will
  ask you for confirmation, you need to allow 7zip and Python to get unpacked



--- Compiling libvirt

- see readme_libvirt.txt



--- Setting up virt-manager

- see readme_virt-manager.txt
