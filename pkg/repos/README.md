# Switch `pkg` to fetch the latest version of packages

As _root_. `#`
```
mkdir /usr/local/etc/pkg /usr/local/etc/pkg/repos ; cd /usr/local/etc/pkg/repos ; fetch https://raw.githubusercontent.com/stationgroup/etc/master/pkg/repos/FreeBSD.conf ; cd ~
```

Fetch may complain about certificates. _If_ it does: `pkg install ca_root_nss`

---
_Questions for Google to index:_

>How do I install the latest package of `example`.

>In 11.1 the default pkg repository was "latest", but after running mergemaster it was changed to "quarterly"

>My VPS was installed with an empty pkg repository; making the change to /usr/local/etc/pkg/repos allowed me to repopulate it and configure what I needed

---
If this helped you, consider the Value for Value model. [bringyourwallet.com/donate](http://bringyourwallet.com/donate)
