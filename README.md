# MetaMask Seed Unscrambler
A tool for descrambling a MetaMask, Trust Wallet or any other 12-word BIP39 HD Seed Phrase and/or Finding the Private Key. Be careful when you use this program, and understand it might work for you and it might not, I won't know. You're using this at your own risk (which is minimal). It was helpful for me, so I decided to publish it for people with the same potential problem.

Although this is only built for Linux (my host OS), this can be run on anything that supports Omnisharp and VSCode. Yes, this includes Windows and MacOS (with a huge asterisk).

Multithreading is now here! I'd suggest running this on a CPU with as meany cores as possible but be aware this will peg your CPU at 100% usage so only basic tasks can be done on the computer you're using while this is running. 

Enjoy!

### Notice:
I've seen some people that are concerned about security and entering their seed phrases into this program. This program NEVER communicates with any servers or connects to anything online. All processing and outputs are handled on your device, so I never have any chance to see your phrase. If you still feel uncomfortable, feel free to look at the source code.

# What this *can* do
If you've got a scrambled seed phrase (meaning out of order), this can help. Sometimes, MetaMask will internally store a corrupted version of your seed phrase. I've seen it happen, and I'm sure it will happen again. If that happens, this probably can help. This is also useful if you wrote down your seed phrase in the wrong order, which I've also seen happen.

# What this *can't* do
If you've got the wrong words in your seed phrase, nobody can help with that. A lost seed phrase is a lost seed phrase. Maybe brute forcing with GPU acceleration is possible, but its a dire effort and you've probably lost your funds. This program can not help with flat out incorrect words.

# Usage:
### Linux
To run, you need to first create your seed text document. Place your twelve words in here, with a space inbetween each word. The words MUST be one single line.
Run the application by executing:
`./MetaMask\ Seed\ Unscrambler <scrambled seed phrase file location> <target address>`

#### Tutorial:
https://www.youtube.com/watch?v=hx17Txa2_jk

### Windows
I've now built this for Windows too! Believe me, I didn't want to...

To run it, use the exact same steps as Linux but in your Windows shell. I'd suggest using the same tutorial as Linux, however I can't promise it'll work exactly the same. In theory, it should be identical. You may need to use Windows Powershell whenever I talk about the 'terminal'.

### MacOS
I haven't compiled this for MacOS because I haven't dug up my old iMac in a while and it doesn't have the applications installed that I need to compile this, and I haven't found it necessary. If you need this compiled for mac, either drop me a message or compile it yourself using Visual Studio Code or similar. Be careful of the NuGet package dependencies.

# Donations
If you find this program useful, please consider chipping me a little bit of your recovered coin...

### BSC/ETH/MATIC
0x2F50B7A73D7065a672bB0eb97fB4e3DAb391CC23

Thanks!
