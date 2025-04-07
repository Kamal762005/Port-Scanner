# Port-Scanner
Port Scanner is a multi-threaded port scanner that scans specied ports on a target host to check if they are open or closed. It utilizes socket programming and threading to perform scanning eciently.

## To check the open ports in your local host:
  ```bash
  netstat -ano
  ```
run this command in your command prompt to check the localhost address with open ports.
## to run the advaanced_scanning.py file
```bash
python3 advaanced_scanning.py -H <local_ip> -P <port_numbers>
```
