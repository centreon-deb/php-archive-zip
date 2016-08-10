Build instructions for the impatient


```bash
curl https://raw.githubusercontent.com/centreon-deb/php-archive-zip/debian/bootstrap | sh
cd php-archive-zip && git deb-pkg -C -U -u 0.1.2 -d origin/debian build
```

Further instruction in the [README.Build.md](README.Build.md) file.
