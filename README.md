# ticket_296660

Notes and code for ticket 296660

## Notes

### Do a install local

From [Stack Overflow](https://stackoverflow.com/a/58532142): 

```r
remotes::install_local
```

or:

```r
devtools::install_local
```

I think we have this on Bianca.

## Convert zip to tar

From [Stack Overflow](https://unix.stackexchange.com/a/756172):

```bash
bsdtar -zcf file.tar.gz @file.zip
```
