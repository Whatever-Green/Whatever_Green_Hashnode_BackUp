## Building and Installing Zoho Docs on Linux (Arch)


The easy Way

Zoho Docs is a online cloud service with 25GB of free storage
Handy things to have

- An arch based distro
- Internet Access
- And an iron will to get this thing working

Installation

Just copy and paste what is here into the terminal, if some commands dont run see if the version numbers have changed
```

git clone https://aur.archlinux.org/zoho-docs-bin.git
cd zoho-docs-bin
makepkg -s
sudo pacman -U zoho-docs-bin-1.9.22-3-x86_64.pkg.tar.zst
```

Now there should be a low quality logo with the title ZOHO DOCS


![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1645195610208/6KGWF3eFM.png)

You have done it no need to thank me.
