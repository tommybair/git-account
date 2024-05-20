# git-account

## Setup

- After cloning the repo, open the terminal into the repo's directory.
  - Install it by running

```bash
python3 -m pip install .
```

- Install sshpass by running

```bash
sudo apt-get install sshpass
```

## Usage

### Add an account

```bash
git-account --add
```

### Switch accounts
  
```bash
git-account --switch <name-of-account>
```

### List accounts

```bash
git-account --list
```

### Switch account on remote device

```bash
git-account --switch <name-of-account> --remote <hostname> <username>
```

- Additionally if you have your ssh keys setup for that device you can use ```--no-password``` to avoid entering the password

```bash
git-account --switch <name-of-account> --remote <hostname> <username> --no-password
```
