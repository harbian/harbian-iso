# harbian-iso
Harbian netinstall ISO

## Merging files into ISO and verify

```
cd dir
../iso_merge.sh
sha256sum harbian-1337.iso
gpg --verify harbian-date-buster-netinstall.iso.asc harbian-1337.iso 
```
