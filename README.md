# XSVCRED-STUDIOSX
music production/ gaming build...
# [TITLE]: hardware-wifi
# [DESCRIPTION]: Firmware and tools for basic WiFi support.
# [STATUS]: Active
# [CAPABILITIES]:
# [TAGS]: Tools and Utilities, Networking
# [MAINTAINER]: Arjan van de Ven <arjan@linux.intel.com>
include(libstdcpp)
include(libglib)
include(NetworkManager-extras)

include(linux-firmware-wifi)
NetworkManager-bin
NetworkManager-config
NetworkManager-data
include(wpa_supplicant)
