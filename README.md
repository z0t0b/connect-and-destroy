## NOTE: Please do not use this project unless you are fully aware of the ramifications and are within legal (and ethical) boundaries. I am not responsible for any misuse of this project. Make sure you know how this works before you run anything!

In your Mac/Linux machine, clone this repo and install `ansible` with a package manager of your choice. To run this on a machine, you must have an account with `sudo` privileges, and you must be able to connect to it via SSH. Modify the `hosts` and `remote_user` sections in `destroy.yml` to match your target machines. Use the `ansible-playbook` command with the path to the `destroy.yml` file and the `-K` option for proper authentication. Consult the `ansible-playbook` man page for further options that may work better for your situation.

Currently this project supports Ubuntu, but will eventually support other operating systems.
