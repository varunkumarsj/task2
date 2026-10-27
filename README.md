
# DevOps Practical Tasks

This repository contains my Git and networking practical exercises performed using Git Bash on Windows.

## Task 1: Git Merge Conflict
- Created branches `branch1` and `branch2`.
- Modified the same line in both branches.
- Merged the branches and resolved the conflict manually.
- Committed the resolved changes.

## Task 2: Git Stash
- Created and committed `stash.txt`.
- Modified the file and saved changes using `git stash`.
- Restored changes using `git stash apply`.
- Verified the changes using `git diff`.

## Task 3: Network IP Information
- Private IPv4: `192.168.1.25`
- Subnet mask: `255.255.255.0`
- Default gateway: `192.168.1.1`
- Public IPv4 was checked using `curl -4 ifconfig.me` (not published for privacy).

## Task 4: Ping Test
- Google DNS (`8.8.8.8`): Average 26 ms, 0% packet loss.
- Router (`192.168.1.1`): Average 4 ms, 0% packet loss.

## Task 5: Traceroute
- Ran `tracert google.com`.
- Destination reached in 6 hops.

## Task 6: DNS Lookup
- Default DNS: `192.168.1.1`
- Google DNS: `8.8.8.8`
- Cloudflare DNS: `1.1.1.1`
- All three successfully resolved `google.com`.

## Tools Used
- Git and Git Bash
- GitHub
- Visual Studio Code
- Windows networking commands



## Basic Networking Commands

1. ping
   Checks whether another computer or server is reachable.
   Example: ping google.com

2. ipconfig
   Displays the computer's IP address, subnet mask, and gateway.
   Example: ipconfig

3. netstat
   Displays active network connections and listening ports.
   Example: netstat -ano

4. nslookup
   Finds the IP address associated with a domain name.
   Example: nslookup google.com
