# fstrim

> Discard unused blocks on a mounted filesystem.
> Only supported by flash memory devices such as SSDs and microSD cards.
> More information: <https://manned.org/fstrim>.

- Trim unused blocks on all mounted partitions that support it:

`sudo fstrim {{[-a|--all]}}`

- Trim unused blocks on a specified partition:

`sudo fstrim {{/}}`

- Display statistics after trimming:

`sudo fstrim {{[-v|--verbose]}} {{/}}`
