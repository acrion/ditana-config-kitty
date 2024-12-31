# ditana-config-kitty

This Arch package provides the Ditana GNU/Linux distribution’s custom configuration for the kitty terminal emulator.

## Overview

Kitty is the default terminal emulator for Ditana GNU/Linux, chosen for its outstanding performance and feature set. This package applies Ditana-specific configurations to enhance the user experience.

## Features

- **Optimized Window Size**: Initial window size set to 155x43 characters (instead of pixels) to ensure consistent text display across different scaling settings.
- **Increased Scrollback**: History increased from 2000 to 8192 lines for enhanced productivity.
- **Customized Layouts**: Default layout changed to "grid", with layout cycling (Ctrl+Shift+L) limited to "grid,horizontal,vertical".
- **Adjusted Font Size**: Default font size changed from 11 to 9.
- **Ditana Branding**: Semi-transparent Ditana logo displayed in the top-right corner of the terminal window.

## Installed together with kitty’s optional dependencies

- imagemagick
- python-pygments
- libcanberra

## Installation

This package is available in Ditana’s repository and automatically installed as part of the [Ditana XFCE desktop environment](https://github.com/acrion/ditana-config-xfce).

## Acknowledgments

Special thanks to Kovid Goyal for creating the fantastic [kitty terminal emulator](https://sw.kovidgoyal.net/kitty). Kitty’s hardware-accelerated rendering and innovative features like [kittens](https://sw.kovidgoyal.net/kitty/kittens_intro/) (e.g., [automatic shell integration on remote hosts](https://sw.kovidgoyal.net/kitty/kittens/ssh) via `kitten ssh`) make it an exceptional choice for Ditana GNU/Linux.

## More Information

For more details about Ditana GNU/Linux, visit [https://ditana.org](https://ditana.org).
