# ansible-spectre-meltdown
## Getting Started

### Prerequisites
```
ansible >= 2.4.0
```

### Installing
```
https://github.com/srekcahrai/spectre_meltdown.git
```

## Running
To install check_spectre_meltdown script and check vulnerabilities
```
ansible-playbook -i "127.0.0.1," --tag "check" main.yml
```

To install patches for Spectre and Meltdown Vulnerabilities
```
ansible-playbook -i "127.0.0.1," --tag "patch" main.yml
```

