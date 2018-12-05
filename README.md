# uvm-1.2
> uvm-1.2 library files from: http://www.accellera.org/images/downloads/standards/uvm/uvm-1.2.tar.gz

tar -xvzf uvm-1.2.tar.gz

find . -name ".nfs*" -type f -print -exec rm {} \;
> ./uvm-1.2/.nfs0000000000a6f85a00000182
> ./uvm-1.2/src/seq/.nfs000000000016f7d600000181
> ./uvm-1.2/src/seq/.nfs0000000001c36e0f00000180
> ./uvm-1.2/src/base/.nfs0000000001934ae40000017f
> ./uvm-1.2/docs/html/files/overviews/.nfs00000000010cd88d0000017e

cd uvm-1.2/src/
ctags --languages=systemverilog -R .

