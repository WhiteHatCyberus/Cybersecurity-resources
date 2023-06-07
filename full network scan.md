# The problem
Want to see which devices are connected to your local network?

# Solution
- Run
```bash
sudo arp-scan --interface=eth0 --localnet
```
> **Note** interface=eth0, may vary according to the network interface you want to scan, for checking that use the `ifconfig` command.
