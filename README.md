# Pi-hole .zip Domain Blocklist

This repository hosts a list of domains serving .zip files, to be used as an ad list for Pi-hole. These domains are known to deliver potentially harmful .zip files that may contain malware, adware, or other unwanted material. By integrating this list into your Pi-hole setup, you can enhance your network's security and minimize exposure to undesirable web content.


## Getting Started

These instructions will help you add this ad list to your Pi-hole setup.

1. Copy the URL of the raw list file from this repository: https://github.com/username/pihole-zip-domains/zip-domains.txt

2. Access your Pi-hole admin interface, typically at http://pi.hole/admin or http://<your_pihole_ip_address>/admin

3. Go to "Group Management" -> "Adlists"

4. At the bottom of the page, paste the copied URL into the address field and click on "Add"

5. Finally, update your gravity list by going to "Tools" -> "Update Gravity", or by running pihole -g from your Pi-hole's command line.




### Disclaimer

This list is provided as-is, and you use it at your own risk. The maintainers of this repository disclaim any responsibility for any issues or problems that may arise from using this list.
