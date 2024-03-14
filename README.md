
# Common attack flow

## Reconnaissance

- Use nmap to scan the network (nmap [scan type] [options] [targets])

### command flags

- -sT (full TCP scan)
- -p (scan for specific ports)
- -6 (enable IPV6 scan)
- -O (enable OS detection)
- -sU (UDP port scan)
- -Pn (dont check if host is up via ping)
- -sS (enable stealth scan)

## Weaponization
- Use ncrack to attempt to break into the target hosts machine. 

### Command flags
- -u (specifies a username)
- -P (a password or a file containing a list of passwords)
- -p (the port number or range of port numbers to target)
- -T (sets the number of threads to use for parelleization)
- -f (a file containing targets by IP or hostnames)
## Exploite and exectue
- Delete any files that contain sensitive or essential information

## command & control
- N/A for this project.