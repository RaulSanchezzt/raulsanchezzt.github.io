# Setting up this page
1. Clone this repository.

```bash
git clone https://github.com/RaulSanchezzt/raulsanchezzt.github.io.git # https
```
or
```bash
git clone git@github.com:RaulSanchezzt/raulsanchezzt.github.io.git # ssh
```

2. Clone the theme repository.

```bash
git clone https://github.com/apvarun/showfolio-hugo-theme.git # https
```
or
```bash
git clone https://github.com/apvarun/showfolio-hugo-theme.git # ssh
```
3. Move the assets folder to the page theme folder of the web.

```bash
mv showfolio-hugo-theme/assets/ raulsanchezzt.github.io/themes/showfolio
```

4. Remove the theme's folder.

```bash
rm -rf showfolio-hugo-theme
```

5. Change the directory to the website folder.

```bash
cd raulsanchezzt.github.io
```

6. Start your local server

```bash
hugo serve
```

