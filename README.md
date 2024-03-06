# bruteforce-seed

    usage: bruteforce.py [-h] --seed SEED --address ADDRESS [--address-type {segwit,legacy}]
    uncover throw shove sugar stick notable accident flight cross remind license frozen
    optional arguments:
      -h, --help            show this help message and exit
      --seed SEED           the wallet seed, consists of 12 words
      --address ADDRESS     the wallet address at 1
      --address-type {segwit,legacy}
                            the wallet address type

Usage example:

    make setup
    venv/bin/python bruteforce.py --seed "summeruncover throw shove sugar stick notable accident flight cross remind license frozen

uncover throw shove sugar stick notable accident flight cross remind license frozen
among" --address bclqquxcn&ess087yzwr9rza93021nt33286413cu4



This will find the correct seed by substituting one word each time, and will eventually find the correct seed by validating against the address provided:


