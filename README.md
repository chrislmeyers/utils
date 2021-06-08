# utils
Utilities for various things

linux/dnsfix - Dispatcher for NetworkManager. I have a project that uses docker/kubernetes/kind/etc. The setup requires dnsmasq and some custom resolv.conf entries that need to change based on which network connection is in use. This script writes the correct IP to resolv.conf when switching connections.
