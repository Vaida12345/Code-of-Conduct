
# FAQs on FinderQuery

## First things first

This App is designed to run on a home network. A company network may have firewalls, and blocks the functionality of this App. Personal hotspot is not recommended, as the latency is high. One should not use this App in a public network, as although it has encryptions built-in, there may be flaws.  


## Initial Connection

### Why can't I connect to the server?

Please double check your IP address and port number, and make sure they match the ones shown on your server. Always ensure to click the *new connections* button on your server, which would show you the IP address and port number.

### Why do I need to enter such a long string?

This string is what keeps your connections safe. The longer it is, the harder it would be for others to guess the code. The App, along with the server, uses this code to encrypt the connections. In fact, this is the only way that the server and the client communicate to share the encryption key. A hash function is used to check the integrity of the code.


## Using this app

### Nothing happened when tapping on a server?

1. Try again. Network can be unstable, and retrying may just fix the error.
2. Ensure you are on the same network as the one you used to establish the first connection to the server. Changing to a different network will certainly change the IP address of the server, and you **need** to reconnect to it, by deleting the other end on server and client first. Returning to the previous network *may* also change the IP address. 
3. Make sure the server and client are not connected to each other. A connected server / client would be shown in green. Though it is not mandatory for the client and server to be disconnected to each other before the client tries to connect to the server, it is a workaround.

### Download speed is slow?

The speed is only determined by your server, your client, and your router. Your internet speed connecting to the outside world has nothing to do with it. Try moving your device closer to the WIFI router.  

### Will it cost any cellular data when using personal hotspot?

No. Nothing leaves your local network, which, in this case, is your personal hotspot. Nothing comes in or goes out, and your ISP has no reason to charge you for anything.

### To where are the files downloaded?

- For files, it is saved to a temp folder, which is deleted when you leave the pages on which the file is downloaded.  
- For folders, it would be saved to your downloads folder on a Mac, or can be found at On my Device > Finder Query on any other devices. One is expected to delete these files on one's own.
