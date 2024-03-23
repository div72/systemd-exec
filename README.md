# systemd-exec

A script for running commands from the environment of a systemd unit. Requires bash, GNU coreutils and sudo.

## Usage

```bash
nobody@example.org $ systemd-exec mariadb bash
mysql@example.org $ echo $GROUP
mysql
```

## License

GNU GPL-3.0. See the LICENSE file for the license text.
