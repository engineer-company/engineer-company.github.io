# engineer-company.github.io

## Initial step

```bash
git clone git@github.com:engineer-company/engineer-company.github.io.git

cd ./engineer-company.github.io

echo "Hello World" > index.html

git add --all
git commit -m "Initial commit"
git push -u origin main
```

## To be able to provide the proper mime-type

```bash
base64 -i './assets/fonts/ubuntu_300.woff2'
base64 -i './assets/fonts/ubuntu_500.woff2'
base64 -i './assets/fonts/ubuntu_700.woff2'
```

## favicon.ico workaround

> Failed to load resource: The requested URL was not found on this server.
> file:///favicon.ico

```bash
base64 -i './favicon.ico'
```

## Check if files are being compressed

```bash
curl -s -H "Accept-Encoding: gzip" -I https://engineer.company/ | grep content-encoding
```

## Start local server

```bash
python3 -m http.server
```

## IP address of the host machine to acces from viratual machine

```bash
http://10.211.55.2:8000
```



Format xml document

> I'll be adding four spaces

```bash
XMLLINT_INDENT="    " xmllint --format sitemap.xml
```


`.gitignore` file

```sh
gi windows,macos,linux,xcode,visualstudiocode > .gitignore
```