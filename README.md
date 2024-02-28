# landing-page

## WSL

WSL can be used to work with a Linux distribution on Windows, without the need to dual boot or run a virtual machine. It is provided by Microsoft natively on Windows 10 and 11, and is relatively easy to install and use.

Follow instructions here to set up and install WSL on Windows:
> https://learn.microsoft.com/en-us/windows/wsl/install
* Recommended to use default settings and install Ubuntu distribution
* Make sure to install WSL**2**
* Usage tips:
  * To close WSL terminal use either `exit` or *ctrl+d* in order to save commands history
  * Windows drives (C:\\, ...) are available in WSL via */mnt/c/*, ...
  * To access WSL files from Windows navigate to *\\\\wsl$* path in explorer
  * To open files in Windows default program from WSL use `wslview <file>`

**Guides:**

- **[Building WSL kernel](https://github.com/dima-lech/wsl2-linux-kernel)** (only for WSL2)

## QEMU

**Guides:**

- **[QEMU lab](https://github.com/dima-lech/linux-course-qemu-lab)**

