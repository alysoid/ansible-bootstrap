# [Catena](https://github.com/alysoid/catena) - Bootstrap Ansible Role

Bootstrap Ubuntu operating system for Catena environment management.

## Locale Environment variables

| Variable                | Environment variable | Default     | Info
| ----------------------- | -------------------- | ----------- | ------------
| `locale_lang`           | $LANG                | en_US.UTF-8 | required
| `locale_language`       | $LANGUAGE            | not set     | not required
| `locale_all`            | $LC_ALL              | not set     | not required
| `locale_numeric`        | $LC_NUMERIC          | not set     | not required
| `locale_time`           | $LC_TIME             | not set     | not required
| `locale_monetary`       | $LC_MONETARY         | not set     | not required
| `locale_paper`          | $LC_PAPER            | not set     | not required
| `locale_identification` | $LC_IDENTIFICATION   | not set     | not required
| `locale_name`           | $LC_NAME             | not set     | not required
| `locale_address`        | $LC_ADDRESS          | not set     | not required
| `locale_telephone`      | $LC_TELEPHONE        | not set     | not required
| `locale_measurement`    | $LC_MEASUREMENT      | not set     | not required

## Timezone Variables

| Variable                | Default | Info
| ----------------------- | ------- | ------------
| `default_timezone`      | Etc/UTC | required
