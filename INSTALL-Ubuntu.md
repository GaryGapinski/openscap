# Ubuntu (17.04) Build

Install the following packages:

- automake
- libtool
- libcurl4-gnutls-dev
- libxml2-dev
- libxslt1-dev
- libpcre3-dev
- libgcrypt20-dev
- libbz2-dev
- swig
- libpython-dev

```
apt install automake libtool libcurl4-gnutls-dev libxml2-dev libxslt1-dev libpcre3-dev libgcrypt20-dev libbz2-dev swig libpython-dev
```

The following packages are optional (but are required if the corresponding probes will be used):

- libacl1-dev (needed for fileextendedattribute probe)
- libgconf2-dev (needed for gconf probe)
- libselinux1-dev (needed for selinuxboolean and selinuxsecuritycontext probes)
- libdpkg-dev, libapt-pkg-dev (needed for dpkginfo probe)
- librpm-dev (required for rpminfo, rpmverify, rpmverifyfile, rpmverifypackage probes)
- libldap2-dev (required for ldap57 probe)
- libopendbx1-dev (required for sql, sql57 probes)
- ??? (required for isainfo probe) (libc6-dev is installed, but no joy) (~~libc6-dev-amd64~~)
- ??? (required for process58 probe)

