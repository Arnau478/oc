# OC - Of course

Do you know how big the `yes` command is? Well, ~30KB! I knew I could do better than that, so I entered the rabbit hole. I ended up hand-crafting an ELF file, literally writing the ELF headers and the instructions itself in binary. But how much smaller is it? Well... **107 bytes**

## "Compiling"
The "source code" (well, it's just hexadecimal) is in oc.hex. It has some comments so that there is some sense to it. To "compile" it (if you can call that compilation) just run `make.sh`. It will take the hexdump and create an actual binary file that you can run.
