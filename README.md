# NowifiloginVPNbypassing
# Stops X-VPN from being allowed to connect to its ips
# X-VPN servers list (Free servers are only in this list as they are the most commonly used among school students.)
Currently iun progress but my gosh darn Thinkpasd dont want to boot into barebones android

#
What is this?
its a ip/domain list so schools/organizations can prevent the use of theese vpns as they are a very huge security risk. I using X-VPN was able to see EVERYTHING on a network with a captive portal. Without even being logged into the captive portal. So I feel that businesses should know theese addresses and block them via firewall.

# Keep in mind!!!!
Theese is evertyhing that came out of the DNS with everything closed exeept for wireshark and X-VPN on a windows pc I would go through this in a test enviroment and make sure it doesent break anything. I will filter it soon. Most of everything that showed up in the dns came up when I clicked connect on the vpn so there might be some windows connections in there. All of the IPS came from the destination collum in wireshark. There are some addresses at the top I was able to fish out using pi hole and blocking them did break UDP (Slightly) TLS - 2 Entirely.
