# Server Project

## In this chapter first I'm introduce how I git and github cli tools

```
I have five defferent server and every ever deffert one from other.
I have FreeBSD (unix like), Red Hat(linux fedora basic destro), Kali Linux (debain base linux destro), Ubunt (also debain base linux desktro) and last MicroSoft OS (Ms Dos).
There according to each OS and their package usage; the installation process also differ.
```

Example One
- pkg install git gh

Example Two
- dnf install git gh

Example Three
- apt install git gh

Example Fourth
- apt install git gh

Example Fifth
- Install-Module -Name git gh or winget install git gh

```
After installation is complete. 
Configure the git version control:
```

- First One
```
    git config --global user.name "$USER"
    git config --global user.email "$USER@gmail.com"
```
## Few basic git command to manage the fiel versioning:
- First:
```
    git add $FILES
```
- Second:
```
    git commit -m "$MESSAGE"
```
- Thirde:
```
    git push origin master
```
I only use these three git command and sometime some alias too.
The most intersting and trick thing all will complete with gh cli

## Few basic gh cli command
- First:
```
    gh auth login
```
- Second
```
    gh repo list
```
- Thirde
```
    gh repo clone
```
- Fourth
```
    gh repo view
```
- Fifth
```
    gh repo read-dir
```

---


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

```
This community.general dependence is needed when we write playbook related with FreeBSD. FreeBSD pkg command don't really work well when we have to write a higher level playbook. I need some ansible provided syntax and rules to follow. Exact like the community.general dependences work with these cases like instead of pkg ansible use pkgng with prefix dependence that ansible galaxy provide as community.general.pkgng:.
```

