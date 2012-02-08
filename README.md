# Parappa (the wrapper)

Parappa (the wrapper) wraps other commands in a REPL

```bash
while read -p $@">" input; do
    $@ $input
done
```

## Example

```
bash>parappa whois
whois>reddit.com
  
...
  
whois>techcrunch.com
  
...
```

Ctrl-C/Ctrl-D to exit.
