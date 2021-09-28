# CEH

1. Recon

1.1 Network:
nmap

1.2 email 
## Email Harvesting with Metasploit 

use auxiliary/gather/search_email_collector
msf  auxiliary(search_email_collector) > show options
set DOMAIN abc.com
set OUTFILE email.txt
exploit
