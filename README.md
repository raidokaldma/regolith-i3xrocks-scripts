# Regolith Status Bar Indicators
https://regolith-linux.org/docs/howto/add-remove-blocklets/

### ~/.config/regolith/i3xrocks/conf.d/10_net-traffic

```
[net-traffic]
command=/path/to/regolith-scripts/net-traffic -b
interval=5
```

### ~/.config/regolith/i3xrocks/conf.d/40_top-process

```
[top-process]
command=/path/to/regolith-scripts/top_cpu_process
interval=1
```
