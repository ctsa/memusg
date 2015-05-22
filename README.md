A 'time'-like utility for Unix that measures peak memory usage.

Works in both interactive and non-interactive environments.

Usage:

```bash
export PATH=$path_to_memusg
memusg my_command
```

Example:

```bash
memusg sleep 2
```

Note (ctsa) this version is forked from jhclark/memusg. The motivating change is to measure peak rss instaead of vmsize
