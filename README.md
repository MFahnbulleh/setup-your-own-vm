# setup-your-own-vm
# Create a VM lab
## Your first VM
## Your second VM

What OS is your VM running? Ubuntu 24.04 LTS (Noble Numbat) 64-bit

What challenges did you face while creating your VM? Receiving error messages that I wasn't sure how to resolve. What troubleshooting steps did you take to resolve those challenges and what did you research? Used my resources (Google, ChatGPT) and Slacked classmates for assistance. Redid steps until it worked.

How much RAM and hard disk space did you allocate to your VM? 4GB RAM and 2 CPU

What happens if you allocate too much RAM? Host system can become slow or unstable, system will not be able to launch the VM, other apps may crash, and system may force close applications causing data loss.

What settings did you change and why? I enabled 3D acceleration and increased the video memory to the maximum allowed (usually 128 MB) in the VM's Display settings. These changes improve graphics rendering, allowing the Ubuntu desktop environment to run more smoothly. I also installed VirtualBox Guest Additions to support better resolution scaling, mouse integration, and clipboard sharing. Lastly, I enabled bidirectional clipboard to allow easier copy-paste between my host and the VM.

How did your VM perform before and after changing the settings? Before making these changes, the VM was sluggish—window movements were choppy, and resolution options were limited. After installing Guest Additions and increasing video memory, the system became more responsive, animations were smoother, and I could resize the VM window with dynamic resolution support. Clipboard sharing also began working seamlessly.

What other settings do you think could be important for optimizing a VM’s performance? Allocating more CPUs (if your host system can support it) can improve multitasking and responsiveness. Increasing base memory (RAM) improves performance, especially when running browsers or development tools inside the VM. Enabling I/O APIC and VT-x/AMD-V in the System settings can support better virtualization features. Using SSD storage for the VM disk file can also significantly reduce load times and improve file operations.
