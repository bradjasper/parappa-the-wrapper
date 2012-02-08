# Parappa (the wrapper)

Parappa (the wrapper) wraps other commands in a REPL

```bash
while read -p $@">" input; do
    $@ $input
done
```

## Example

```
parappa whois
whois>reddit.com
  
Whois Server Version 2.0
...
  
whois>techcrunch.com
  
Whois Server Version 2.0
...
```

Ctrl-C/Ctrl-D to exit.
