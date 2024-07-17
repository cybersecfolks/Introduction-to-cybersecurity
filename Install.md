# Kali Linux Installation on windows:
To install kali linux on windows we'll need an hypervisor. An hypervisor is a software that can be used to run multiple operating systems on our host machine. Our hypervisor of choice for this course would be virtualbox.
### Installing VirtualBox:
Click this [link](https://download.virtualbox.org/virtualbox/7.0.20/VirtualBox-7.0.20-163906-Win.exe) to install the latest release of virtualbox for windows. 

Once virtualbox is downloaded in your browser, click "open file" and follow the installation prompts to install virtualbox on your machine.

![vbox1](https://github.com/user-attachments/assets/379f440a-756f-4411-b722-d4cb7e5deb60)

You are likely to come accross this error:

![error](https://github.com/user-attachments/assets/6ec0157a-356c-4bd8-a196-0b93243dcc5f)

To fix that, download the microsoft visual c++ redistibutable package from this [page](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170). Scroll down and download the suitable version for your computer's architecture.

![visual](https://github.com/user-attachments/assets/e41f25ad-ed40-40fa-9033-60b3b3d5fc8b)

After installing virtualbox then we can download the kali image.
## Downloading kali iso:
Download the kali linux iso [here](https://cdimage.kali.org/kali-2024.2/kali-linux-2024.2-installer-amd64.iso)
## Creating our virtual machine:
Follow these steps to create your kali virtual machine in virtualbox

![vm](https://github.com/user-attachments/assets/5223ccf9-2c8c-4666-8b2f-b9f2d3599de8)

- Click new

![vm2](https://github.com/user-attachments/assets/aaaf7cb2-2794-4f1c-af43-4aaa0c2a1cb3)

- Fill in a name for your virtual machine in the name field.
- Click the downward arrow in the "ISO Image:" field then click other, it will show you your file library, locate your kali iso (it should be in your downloads folder) then select it.

![vm3](https://github.com/user-attachments/assets/1c8dbefa-d063-4d30-be01-90f2200aa8b2)

- Click next

![vm4](https://github.com/user-attachments/assets/1f129453-c6ee-4a6d-aab5-5fcebe1fd472)

You can decide to allocate more RAM or CPU usage to your virtual machine if your computer is capable.

- Click next

![vm5](https://github.com/user-attachments/assets/1382ebb0-a8ac-4fc5-87c8-1db4f223df06)

- Click next

![vm6](https://github.com/user-attachments/assets/b03b56b9-3d2d-44c3-b30b-3245da66ec3c)

- Click finish

![vm7](https://github.com/user-attachments/assets/3ffc8954-7107-4f4c-990e-af6fa23d3e9f)

Now our kali virtual machine is ready. Click start to fire it up







