# wireshark_plugins

This repo contains wireshark plugins for different protocols/robots which allows to debug network logs more easily.

## Installation

Copy the plugin lua file to the wireshark plugins folder:

```bash
mkdir -p ~/.local/lib/wireshark/plugins
cp extended_simple_message.lua ~/.local/lib/wireshark/plugins
```

Note: Delete `~/.local/lib/wireshark/plugins/packet-simplemessage.lua` if it exists. Wireshark will otherwise report an error because of duplicate definitions of the 'same' plugin.
