# Example IP addressing

LAN Network: 10.255.255.0/24 <br>
Subnet: 255.255.255.0 <br>
254 usable host addresses per subnet (excluding network and broadcast)

## Example IP ranges

| Range                   | Purpose               | Example                 |
| :---------------------- | :-------------------- | :---------------------- |
| 10.255.255.1 - 19       | Network Infra         | Network hardware        |
| 10.255.255.20 - 39      | DNS & Proxy & Access  | DNS, Proxy, VPN         |
| 10.255.255.40 - 59      | Monitoring & Logging  | TBD                     |
| 10.255.255.60 - 79      | Applications          | Streaming, Dashboard    |
| 10.255.255.80 - 99      | Datastore             | Backups, NAS            |
| 10.255.255.100 - 199    | Expansion             | Future services         |
| 10.255.255.200 - 254    | DHCP Clients          | Laptops, phones         |

## Example IP assignments

| Service      | IP              |
| :----------- | :-------------- |
| Gateway      | 10.255.255.1    |
| Hypervisor   | 10.255.255.2    |
| DNS-1        | 10.255.255.20   |
| DNS-2        | 10.255.255.21   |
| Proxy        | 10.255.255.23   |
| VPN          | 10.255.255.24   |
| Dashboard    | 10.255.255.60   |
| Streaming    | 10.255.255.61   |