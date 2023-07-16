## open-electrons

[![Build and Deploy](https://github.com/open-electrons/home/actions/workflows/gh-pages.yml/badge.svg)](https://github.com/open-electrons/home/actions/workflows/gh-pages.yml)

This project encompasses the documentation and informational content for all [open-electrons projects](https://github.com/open-electrons)

## Run Locally

1. Install Hugo

2. Clone this repository including submodules, as a hugo theme is used as a git submodule

```
git clone --recurse-submodules https://github.com/open-electrons/home.git
```

3. Navigate to the project directory and to run, type the following command from the project root folder

```
hugo serve
```

5. Open http://localhost:1313/ (by default)

That's it! Any project changes will be automatically reflected on your local server.

To keep up-to-date with the changes on the submodules (relearn theme), use the following command:

```
git submodule update --recursive --remote
```

[![HitCount](https://hits.dwyl.com/open-electrons/home.svg?style=flat-square&show=unique)](http://hits.dwyl.com/open-electrons/home)
