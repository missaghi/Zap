# Zap
Running Zap on iOS connected to remote LND on windows via OpenVPN running on windows


Getting this to work took a lot of resources and trial and error, so I wanted to collect the end result into a tutorial that might save someone some time. A lot of the tutorials out there were either outdated or not quite my use case which made thisngs tricky.

Here is the stack:

Windows Server: (static-ish IP)
- bitcoin full node
- lnd (lighting node)
- OpenVPN
- To-Do: DynDNS

iOS iPhone
- OpenVPN connect
- Zap

Here are the tutorials
- [Setting up OpenVPN](https://www.reddit.com/r/OpenVPN/comments/81q2q6/guide_how_to_set_up_openvpn_server_on_windows_10/)
Notes:
1. Easy-rsa is no longer included, you have to get it from here:[https://github.com/OpenVPN/easy-rsa/releases]
2. You can monitor the OpenVPN by cliking on the notification tray thing
