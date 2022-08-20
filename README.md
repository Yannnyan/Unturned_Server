# Unturned_Server



# Prerequeisites


### Setting up a static nat ip address
![staticIPFiltered](https://user-images.githubusercontent.com/82415308/185755265-9d9f8352-4d45-4a5a-9586-a94ad599ab0b.png)


### Setting DMZ on the router
![DMZFiltered](https://user-images.githubusercontent.com/82415308/185755276-afc1f44a-004f-4164-a1be-dc73108fae36.png)


### Setting port forwarding on the router

![PortForwardFiltered](https://user-images.githubusercontent.com/82415308/185755288-345b1484-8017-4bc7-b7d4-b0678d9a6b4d.png)



### Unturned dedicated server installation using steamCMD

1. Login to SteamCMD anonymously:

		login anonymous

2. Download the server:

		app_update 1110390

	_Note: this command can also be used to update the server._

3. Close SteamCMD:

		quit

4. The server files are now in the ...SteamCMD\steamapps\common\U3DS directory.

-----------------------------------------------

# Editing the server files and comamnds

### Setting the commands file

![GameTokenFiltered](https://user-images.githubusercontent.com/82415308/185756062-74c82875-9f5f-4011-83ca-64e850f6f7e2.png)
* The first line is the unique server id (i.e login-token) in hex, specified to find that particular server on everybody's client's in-game browser
* the other parameters are straight forward properties of the server such as map difficulty, maxplayers, name etc

### Generating Login-token
![Login_token_filtered](https://user-images.githubusercontent.com/82415308/185756318-0d756818-1e6c-4321-8d90-50351e161502.png)

## adding in-game mods
Community RocketMod plugins https://github.com/RocketModPlugins

