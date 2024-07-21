# WindowsGSM.ForgeMC
🧩 WindowsGSM plugin for supporting Minecraft: Forge Server

> This project is a derivative work of [WindowsGSM.PaperMC](https://github.com/BattlefieldDuck/WindowsGSM.PaperMC). I am not an expert of WindowsGSM nor its plugins; I have simply ported over files from the PaperMC plugin to enable the management of Forge servers within WindowsGSM. Use at your own risk.

## Requirements
[WindowsGSM](https://github.com/WindowsGSM/WindowsGSM) >= 1.21.0

## Installation
1. Download the Plugin via the green Download Code Button or use [latest](https://github.com/Raziel7893/WindowsGSM.ForgeMC/releases/latest) release if available
1. Move the **ForgeMC.cs** folder to **plugins** folder
1. Click the **[RELOAD PLUGINS]** button or restart WindowsGSM

## License
This project, excluding any `**/*.png` files, is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

[ForgeMC.cs/author.png](ForgeMC.cs/author.png) is created by [@taiyaki_tv](https://twitter.com/taiyaki_tv) and reserved for use by me, dwhitacre.

[ForgeMC.cs/ForgeMC.png](ForgeMC.cs/ForgeMC.png) is licensed by [MinecraftForge](https://github.com/MinecraftForge/MinecraftForge).


### Not having an full IPv4 adress ( named CCNAT or DSL Light )
No game or gameserver supports ipv6 only connections. 
- You need to either buy one (most VPN services provide that option. A pal uses ovpn.net for his server, I know of nordvpn also providing that. Should both cost around 7€ cheaper half of it, if your already having an VPN)
- Or you pay a bit more for your internet and take a contract with full ipv4. (depending on your country)
- There are also tunneling methods, which require acces to a server with a full ipv4. Some small VPS can be obtained, not powerfull enough for the servers themself, but only for forwarding. I think there are some for under 5€), the connection is then done via wireguard. but its a bit configuration heavy to setup) 

Or you connect your friends via VPN to your net and play via local lan then.
Many windowsgsm plugin creators recommend zerotier (should be a free VPN designated for gaming) , see chapter below (or tailscale, but no howto there)

## How can you play with your friends without port forwarding?
- Use [zerotier](https://www.zerotier.com/) folow the basic guide and create network
- Download the client app and join to your network
- Create static IP address for your host machine
- Edit WGSM IP Address to your recently created static IP address
- Give your network ID to your friends
- After they've joined to your network
- They can connect using the IP you've created eg: 10.123.17.1:7777
- Enjoy

### Support
[WGSM](https://discord.com/channels/590590698907107340/645730252672335893)

### Give Love!
[Buy me a coffee](https://ko-fi.com/raziel7893)

[Paypal](https://paypal.me/raziel7893)
