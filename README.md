## MangaLoader (Bot)
Telegram RoBot to Upload manga/comic.

### Deploy to heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/X-Gorn/MangaLoader.git)

#### Features:

👉 Uploading from [supported resources](https://manga-py.com/manga-py/#resources-list) as PDF/ZIP/Folder (each chapter) | Uploaded as Zipfile

👉 `/cleandir` to clean your download directory if bot are stuck

#### How to use?!

* Send manga url from [supported resources](https://manga-py.com/manga-py/#resources-list), for url example [read this](#url-options-and-examples)
* Select subdirs option
* Wait a few minutes and the bot will send your manga

#### URL options and examples

`https://komikid.com/manga/updater -s 5` - will skip 5 chapters and start from chapter 6-end

`https://komikid.com/manga/updater -c 5` - will start from chapter 1-5

`https://komikid.com/manga/updater -s 5 -c 5`  -  `-s 5` will skip 5 chapters and `-c 5` will start from chapter 6-10

