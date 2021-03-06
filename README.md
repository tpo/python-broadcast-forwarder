# Python Broadcast Forwarder #

pbf.py listens for directed broadcasts and forwards them over the correct
interface. Examples for directed broadcasts are Wake-on-LAN and Windows
SCCM.

pbf.py has been tested on Linux.

## Getting started ##

### Prerequisites ###
Python needs to be installed on your router.

### Installing ###
1. Copy the file pbf.py on your Linux router
2. Set the correct permissions, for example
 `chown root:root pbh.py
chmod 755 pbh.py`
3. Run the script using the command
`pbf.py -p Port -b Broadcast_IP`

## Testing ##
1. Start the script on your router.
2. Send a directed broadcast to the router.
3. Check if the broadcast arrives in the correct subnet.
