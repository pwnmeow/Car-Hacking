====================
┌─[✗]─[elliot@parrot]─[~/Desktop/car Hacking/icsim]
└──╼ $modprobe vcan 

┌─[✗]─[elliot@parrot]─[~/Desktop/car Hacking/icsim]
└──╼ $dmesg

┌─[✗]─[elliot@parrot]─[~/Desktop/car Hacking/icsim]
└──╼ $ip link add dev vcan0 type vcan

┌─[✗]─[elliot@parrot]─[~/Desktop/car Hacking/icsim]
└──╼ $ip link set up vcan0

//sniffer started 
┌─[✗]─[elliot@parrot]─[~/Desktop/car Hacking/icsim]
└──╼ $cansniffer -c vcan0

