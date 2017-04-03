
- Run without port command line -


sudo iptables -t nat -A PREROUTING -p tcp --dport 80 -j REDIRECT --to-ports 3001
