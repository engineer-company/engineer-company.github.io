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