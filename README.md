<div align="center">

<h1 align="center">FishForYou</h1>

<img src="https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-Semantic-e10079.svg?style=flat-square" alt="Semantic Release"/>
<img src="https://img.shields.io/badge/Maintain-Yes-blueviolet.svg?style=flat-square&logo=Chakra-Ui&color=90E59A&logoColor=green" alt="status" >
<img src="https://img.shields.io/gitlab/v/tag/oeyoews/tw5?color=green&logo=FastAPI&style=flat-square" alt="tag">

<hr>

<img src="https://cdn.jsdelivr.net/gh/oeyoews/img/koi-fish.png" width=128/>

</div>

<hr>

## 📢 What's the tw5?

<!-- - A customize tiddlywiki5 edition -->

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=FiraCode&color=7279F3&vCenter=true&lines=+A+customize+tiddlywiki5+edition" alt="Typing SVG" /></a>

## 🚨 NOTE

> All customize style just for current tiddlywiki5 file, not suit for vanilla tiddlywiki.

## ShowCases

- Demo: [preview address](https://oeyoew.fun) or [tw5 vercel address](https://tw5s.vercel.app/)
- Video Demo: [preview video](https://www.bilibili.com/video/BV13a411D7G6?spm_id_from=333.999.0.0)
- Code: [gitlab](https://gitlab.com/oeyoews/tw5) and [github](https://github.com/oeyoews/tw5)

<div align="center">

| <img src="img/preview.png" alt="preview" width=512/> | <img src="img/01.png" alt="preview" width=512/> | <img src="img/01.png" alt="preview" width=512/> |
| :--------------------------------------------------: | :---------------------------------------------: | ----------------------------------------------- |

</div>

## ⛴️ Features

- based web browser
- fastly visited
- customize shortkeys
- customize file struct, ui and etc
- music player and random sentence on the bottom
- fastly deploy site with multi types, like github actions, gitlab runner, vercel and etc
- background run use systemd, startup automatically
- better experience on pc and iphone

## 🧳 Install

```bash
curl -fsSL oeyoew.fun/install-tw5.sh | bash
```

## Struct

```bash
📂tw5
├── 📂docs
├── 📂img
├── 📂package.json
├── 📂scripts
├── 📂static
├── 📂tiddlers
├── 📝LICENCE
├── 📝README.md
├── 📝tw5.service
└── 📝tiddlywiki.info
```

## as service with user

```bash
cp tw5.service ~/.config/systemd/user
systemctl --user daemon-reload
systemctl --user start tw5.service
```

## 🏡 Running

```bash
yarn install  # install dependencies
yarn start    # start tiddlywiki
```

```bash
tiddlywiki folderName --init server  # init new folder
```

```bash
tiddlywiki --listen port=8080 host=0.0.0.0  # listen 0.0.0.0
```

## 🌳 TODO

[TODO](docs/TODO.md)

## 🔫 CHANGELOG

[CHANGELOG](docs/CHANGELOG.md)

<!-- <img src="https://img.shields.io/badge/License-GPL--3.0-green.svg?style=flat-square&logo=GNU&color=df967f&label=License" alt="license"> -->
<!-- <img src="https://img.shields.io/badge/System-Linux-white.svg?style=flat-square&logo=linux&logoColor=white&color=BB9AF7" alt="system"> -->
<!-- <img src="https://img.shields.io/badge/Github-Yes-green.svg?style=flat-square&logo=github&label=Github&logoColor=cyan" alt="github"> -->
<!-- <img src="https://img.shields.io/badge/Gitlab-Yes-ffcc00.svg?style=flat-square&logo=gitlab&label=Gitlab" alt="gitlab"> -->
<!-- <img src="https://img.shields.io/badge/GIT-Yes-green.svg?style=flat-square&logo=git&label=GIT" alt="git"> -->
