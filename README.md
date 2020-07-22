### Who am I?

I'm serebit (also known as Campbell, or "Ginger"), and I build software that I hope can be useful to others.

### Why are all your repositories mirrors?

Because I prefer GitLab, but want to push to GitHub as well for discoverability purposes.

### What have you built?

#### Wraith Master (written in Kotlin/Native)

Wraith Master is a graphical and command-line configuration tool for the RGB LEDs on AMD's Wraith Prism stock cooler. It was created out of a desire to be able to change the LED settings on Linux as well as Windows, and was built using Wireshark to reverse-engineer the USB packets being sent by Cooler Master's official Windows configuration tool. It uses libusb for USB communication, and GTK3 for the GUI.

#### Carbontray (written in C)

Carbontray is a light and configurable implementation of the X system tray for the [Budgie desktop environment](https://github.com/solus-project/budgie-desktop). At roughly 1000 lines of code vs the previous tray's 3000, it offers additional settings such as individual icon spacing and fixes numerous issues, some dating as far back as 2017. Carbontray is contained entirely in the Budgie repository on GitHub.

#### Strife (written in Kotlin/JVM and Kotlin/Native)

Strife is an idiomatic Kotlin wrapper for Discord's bot API. While currently no longer in active development, it stands as a fast and easy-to-use implementation with a well-structured and platform-agnostic internal architecture.
