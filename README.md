# Common useful playbooks and other Ansible stuff
- docker
- ... open PR or issue to lmk what else

## Usage
1. edit `hosts.ini` and `ansible.cfg` as needed. Mainly keys and target host :) 
2. use to command below to run a playbook. You can limit a subset of hosts with `-l linode` for example, where linode are written in hosts.ini as 

```bash 
[linode]
17.33.22.11

```
Well you get the idea ...:)

3. Run the playbook. If you need more info, just add `-vvvvvvvvvvvvv` 

```bash 
ansible-playbook <playbook.yml> -i hosts.ini -v 

```

## License

MIT or 0FUCKSGIVEN or SERVERMIGHTBURN
