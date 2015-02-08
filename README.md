# Password manager

A simple, command-line based, password manager.

It uses AES 256 encryption to store passwords in a file. This allows me to
keep a USB key with my passwords on it, along with the binaries for this
password manager for different platforms (Linux, OSX, Windows).

I'm just getting started. The goal is to have the following commands available:

```
# Tries to find the entry for the app you're most likely looking for.
p get <approximate-app-name>

# Adds an entry with this username. The password is retrieved via STDIN.
p add <app-name> <username>

# Removes an entry.
p del <approximate-app-name>

# Adds a new entry with an automatically generated password.
p gen <app-name> <username>
```

Online sync is not planned at the moment. But I'm open to discussion in that
regard.

Please open an issue or a pull request for bug reports, ideas, etc.
