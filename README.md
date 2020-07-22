### Who am I?

I'm serebit (also known as Campbell, or "Ginger"), and I build software that I hope can be useful to others.

### Why are all my repositories mirrors?

Because I prefer GitLab, but want to push to GitHub as well for discoverability purposes.

### How can I be contacted?

I tend to avoid making my email address public to reduce spam. If you'd like to contact me by email, use the contact form on my website [here](https://serebit.com/contact/). It'll send an email to my main inbox, and I'll respond as soon as I'm able.

### What have I built?

#### Wraith Master (written in Kotlin/Native)

Wraith Master is a graphical and command-line configuration tool for the RGB LEDs on AMD's Wraith Prism stock cooler. It was created out of a desire to be able to change the LED settings on Linux as well as Windows, and was built using Wireshark to reverse-engineer the USB packets being sent by Cooler Master's official Windows configuration tool. It uses libusb for USB communication, and GTK3 for the GUI.

#### Strife (written in Kotlin/JVM and Kotlin/Native)

Strife is an idiomatic Kotlin wrapper for Discord's bot API. While currently no longer in active development, it stands as a fast and easy-to-use implementation with a well-structured and platform-agnostic internal architecture.

### What have I contributed?

#### Carbontray for Budgie (written in mostly C and a bit of Vala)

Carbontray is a light and configurable implementation of the X system tray for the [Budgie desktop environment](https://github.com/solus-project/budgie-desktop). At roughly 1000 lines of code vs the previous tray's 3000, it offers additional settings such as individual icon spacing and fixes numerous issues, some dating as far back as 2017. Carbontray is contained entirely in the Budgie repository on GitHub.

#### Packages for Solus

I maintain numerous packages for the [Solus Linux distribution](https://getsol.us), including JDK8, JDK11, Gradle, Kotlin/Native, and my own Wraith Master tool, along with miscellaneous packages such as Just and Kitty. I was the one who trawled through tens of Java packages to upgrade them all to Java 11.
