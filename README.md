Same as https://sourceforge.net/projects/automysqlbackup/
Just added support for multiple mysql deamons running (on different ports).
It allows you to specify custom config in parameter `automysqlbackup [config_path]
`
And allows to define PORT number in the config.

Usage:

```
automysqlbackup /etc/default/automysqlbackup-docker
```