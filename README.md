# harbian-iso
Harbian netinstall ISO

## Spliting the files due to size limited by github

```
split -b 70M harbian-date-buster-netinstall.iso harbian-iso_
```

## Merging files into ISO and verify

```
cd dir
../iso_merge.sh
sha256sum harbian-1337.iso
gpg --verify harbian-date-buster-netinstall.iso.asc harbian-1337.iso 
```
