# IPTables Firewall Basics

IPTables is used to configure firewall rules in Linux.

---

## View Rules

$ sudo iptables -L

---

## Chains

| Chain   | Description |
|--------|-------------|
| INPUT  | Incoming traffic |
| OUTPUT | Outgoing traffic |
| FORWARD| Forwarded packets |

---

## Allow SSH

$ sudo iptables -A INPUT -p tcp --dport 22 -j ACCEPT

---

## Block SSH

$ sudo iptables -A INPUT -p tcp --dport 22 -j DROP

---

## Save Rules

$ sudo service iptables save
