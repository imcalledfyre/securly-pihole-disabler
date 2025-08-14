# securly-pihole-disabler
# Status: unpatched as of ChromeOS v138

## Your district MUST ALLOW you to change / input custom DNS for this to work, for now.

Use pi-hole to block securly!! blocks securly.com, plus all their tracking IPs (as far as i know of)
Update: This meathod DOES actually work!
In PiHole, go to the lists tab, and paste `https://raw.githubusercontent.com/imcalledfyre/securly-pihole-disabler/refs/heads/main/hosts` as a blocklist, then reboot your raspberry pi, then in your chromebook set the DNS to:

raspberrypi's ip
1.1.1.1
0.0.0.0
0.0.0.0

I am working on a bypass for DNS changing being blocked
you may use my list and pls add this to the ext-remover page!!!
