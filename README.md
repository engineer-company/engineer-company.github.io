# engineer-company.github.io

```bash
git clone git@github.com:engineer-company/engineer-company.github.io.git

cd ./engineer-company.github.io

echo "Hello World" > index.html

git add --all
git commit -m "Initial commit"
git push -u origin main
```

Generating Favicons using ImageMagick on the Command-Line

```bash
convert profile.png -bordercolor white -border 0 \
      \( -clone 0 -resize 16x16 \) \
      \( -clone 0 -resize 32x32 \) \
      \( -clone 0 -resize 48x48 \) \
      \( -clone 0 -resize 64x64 \) \
      -delete 0 -alpha off -colors 256 favicon.ico
```

To be able to provide the proper mime-type:

```bash
base64 -i './assets/fonts/ubuntu_300.woff2'
base64 -i './assets/fonts/ubuntu_500.woff2'
base64 -i './assets/fonts/ubuntu_700.woff2'
```

Failed to load resource: The requested URL was not found on this server.
file:///favicon.ico

```bash
base64 -i './favicon.ico'
```

Check if your files are being compressed:

```bash
curl -s -H "Accept-Encoding: gzip" -I https://engineer.company/ | grep content-encoding
```

Start local server

```bash
python3 -m http.server
```

IP address of the host machine to acces from Paralleles

```bash
http://10.211.55.2:8000
```