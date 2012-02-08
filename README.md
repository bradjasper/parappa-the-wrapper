# Parappa (the wrapper)
Parappa (the wrapper) wraps other commands in a REPL

## Example
> parappa whois

> **whois>**reddit.com

> Results...

> **whois>**techcrunch.com

> Results...

## Code

> while read -p $@">" input; do
>   $@ $input
> done

Ctrl-C/Ctrl-D to exit.
