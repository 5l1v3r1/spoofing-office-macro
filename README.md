This repository contains an example of a VBA macro spawning a process with a spoofed parent and command line. Companion blog post: [Building an Office macro to spoof parent processes and command line arguments](https://blog.christophetd.fr/building-an-office-macro-to-spoof-process-parent-and-command-line)

## Demo

Click for full size.

![Demo](https://user-images.githubusercontent.com/136675/54154646-49e44780-443a-11e9-998d-ec1f54a83437.gif)


## Notes

This PoC was tested on Windows 10 with Office Professional Plus 2016, version 1902. It will only work on 32-bit Office versions (on a 32 or 64-bit Windows version). If you have access to a 64-bit Office version and would like to contribute, please do!

The size of the original command line stored in [`originalCli`](https://github.com/christophetd/spoofing-office-macro/blob/master/macro.vba#L260) needs to be greater than the size of the real one stored in [`cmdStr`](https://github.com/christophetd/spoofing-office-macro/blob/master/macro.vba#L311)

## Acknowledgments & inspiration

- ["Red Teaming in the EDR age"](https://www.youtube.com/watch?v=l8nkXCOYQC4) by Will Burgess 
- https://blog.xpnsec.com/how-to-argue-like-cobalt-strike/
- https://twitter.com/subtee

## Disclaimer

You are solely responsible for the use you make of this PoC. I assume no liability for any misuse or damage caused by this program.
