# wattsonic
This is a Wireshark dissector for Wattsonic inverters. It sends data to 2 IP addreses in my case. I tried to parse some fields I found out (check out doc directory). I use Modbus to query the device, but if you want you can do it with this too.

# How

Create a mirrored port or capture on your router/modem. Filter on port 5743. Copy the `wattsonic.lua` to your Wireshark plugins folder.

# Why use this when you can also query with Modbus?

I wanted to create a Wireshark dissector for fun, this simple protocol seemed simple enough.
