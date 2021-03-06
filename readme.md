# pixiv-dl-preview

> pixiv downloader with image preview

<img src="screenshot.gif">

## Install

```
$ npm install --global pixiv-dl-preview
```

## Usage

```
$ pixiv-dl-preview

  pixiv downloader with image preview

  Usage
    $ pixiv-dl-preview [input]

  Options
    --uername, -u   pixiv username (use cache)↲
    --password, -p  pixiv password (use cache)↲
    --output, -o    output directory [Default: curret dir]
    --name, -n      custom filename
    --delay, -d     delay time (ms) [Default: 3000]
    ranking         ranking mode
      day | week | month | day_male | day_female | week_original | week_rookie | day_mang
      day_r18 | day_male_r18 | day_female_r18 | week_r18 | week_r18g

  Examples
    $ pixiv-dl-preview リゼロ10000users入り --username hoge --password fuga
    $ pixiv-dl-preview リゼロ10000users入り --output rezero --name user.account-title
    $ pixiv-dl-preview ranking day --output rezero --name user.account-title
```

## License

MIT © [akameco](http://akameco.github.io)
