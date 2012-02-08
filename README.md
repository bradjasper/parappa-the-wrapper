# Parappa (the wrapper)
Parappa (the wrapper) wraps other commands in a REPL

> while read -p $@">" input; do

>   $@ $input

> done

## Example
> parappa whois

> **whois>**reddit.com

> Results...

> **whois>**techcrunch.com

> Results...

Ctrl-C/Ctrl-D to exit.
