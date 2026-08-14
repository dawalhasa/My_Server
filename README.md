# Server Project

## I have five defferent servers.
- First FreeBSD (considered best server)
- Second Red Hat (interprisist most favored and secured OS)
- Thirde Kali Linux (networking tourble shutting and pentesting purpose)
- Fourth Ubuntu (the one most comman linux OS and favored by all the AI agent)
- Last but not the least (Window MS Dos for practising)

## I operate all these server from my Mac M1
```
Actually Apple is very expensive but the battery is remarkable and long lasting for hours and hours.
Therefore I prefer Mac as my main server so that I don't have to bother about charging again and again and having trouble about carry charger all the time with me.
```

## There are few very intersting command to practice related with freebsd

- ansible all -Kb -m raw -a "pkg update"                           
- ansible all -Kb -m raw -a "pkg install -y python"                           

```
This raw module is very instersting. Not like other OS, freebsd have their own some special syntax like this raw module.
When I use playbook; this syntax should prefix with ansible.builtin.
```

## There are few dependencies to install from ansible-galaxy collection

1. ansible-galaxy collection install community.general
2. ansible-galaxy collection install ansible.posix
