# bruteforce-seed

    usage: bruteforce.py [-h] --seed SEED --address ADDRESS [--address-type {segwit,legacy}]
    
    optional arguments:
      -h, --help            show this help message and exit
      --seed SEED           the wallet seed, consists of 24 words
      --address ADDRESS     the wallet address at 0
      --address-type {segwit,legacy}
                            the wallet address type

Usage example:

    make setup
    venv/bin/python bruteforce.py --seed "summer

true

witness

diamond

laugh

sweet
logic
fetch
pumpkin
edge
stick
among" --address bclqquxcn&ess087yzw
r9rza93021nt3328641
3cu4

This will find the correct seed by substituting one word each time, and will eventually find the correct seed by validating against the address provided:

summer

true

witness

diamond

laugh

sweet
logic
fetch
pumpkin
edge
stick
among
