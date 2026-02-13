# Prize-winning stuff

It is sometimes hard to let go.

A Rust function you wrote.
A short document you edited.
A nice article you read.

For all of these situations, just:
```
pws <stuff-thats-hard-to-let-go-of>
```
...and all will be moved into `~/PWS/<timestamp>/` (e.g., `~/PWS/2026-02-feb-13-fr-08h-15m-30s/`)

## Options

- `-c, --copy` - Copy files instead of moving them
- `-h, --help` - Show help message

## Examples

```bash
pws file.txt              # Move file.txt
pws -c file.txt dir/      # Copy file.txt and dir/
pws *.log                 # Move all .log files
```
