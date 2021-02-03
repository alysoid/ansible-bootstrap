# [Catena](https://github.com/alysoid/catena) - Bootstrap Ansible Role

Bootstrap Gnu+Linux systemd based operating systems via Ansible.

## Role default variables

| Variable           | Default     | Info
| ------------------ | ----------- | --------------------------------------
| `keymap`           | us          | Used by localectl set-keymap
| `locale`           | en_US.UTF-8 | Used by localectl set-locale LANG=
| `language`         | en_US.UTF-8 | Used by localectl set-locale LANGUAGE=
| `timezone`         | Etc/UTC     | Used by timedatectl set-timezone
