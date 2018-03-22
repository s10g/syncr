# syncr
Self-contained shell script and configuration to set up rsyncing between two locations.

## Howto
Edit the script to set remote host, remote path and other things. Save script in the directory you want to sync; it will sync that directory and any directory beyond that (unless excluded from synchronising).

Run like this:
```
./syncr [upload|download|delete]
```
