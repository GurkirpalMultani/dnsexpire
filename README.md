# dnsexpire
PHP tool to test CNAME expiration date of a subdomain list  
Note that this is an automated tool, manual check is still required.  

## Install

```
git clone https://github.com/gwen001/dnsexpire
```

## Usage

```
Usage: php dnsexpire.php [OPTIONS] -f <subdomain|input file>

Options:
	-a	set alert for result output, default=30 days
	-f	subdomains list source file
	-h	print this help

Examples:
	php dnsexpire.php -f example.com
	php dnsexpire.php -a 10 -f dns.txt
```

<img src="https://raw.githubusercontent.com/gwen001/dnsexpire/master/preview.png" />


I don't believe in license.  
You can do whatever you want with this program.


