<h1 align="center">Krew Wiki</h1>

<h1 align="center">
    <img src="https://raw.githubusercontent.com/Krew-io/krew-wiki/master/docs/assets/img/logo.png" align="center"/>
</h1>

<h3 align="center">A wiki for the online game Krew.io</h3>

<p align="center">
    <img src="https://img.shields.io/github/contributors/Krew-io/krew-wiki?style=for-the-badge&color=f26248">
    <img src="https://img.shields.io/github/last-commit/Krew-io/krew-wiki?style=for-the-badge&color=f26248">
    <img src="https://img.shields.io/website?style=for-the-badge&down_color=ff4b3b&down_message=offline&up_color=90de31&up_message=online&url=https%3A%2F%2Fwiki.krew.io">
</p>

---

## Contribute
Make sure you have NodeJS and npm installed before continuing.

Fork the repository and clone it.

All of the wiki is made in markdown, which is essentially text files with additional formatting. You can also add HTML elements within markdown for more complex elements. If you are unfamiliar with markdown formatting, check out [this](https://www.markdownguide.org/cheat-sheet/) website to view the basics of markdown formatting.

To test your changes, install `docsify-cli` globally with npm:
```
npm i -g docsify-cli
```

Afterwards, navigate to the parent directory of the `docs` folder and start docsify:
```
docsify serve docs
```

It will then host a webserver on `http://localhost:3000`, where you can view your changes.

### Troubleshooting

If you get an error about execution policies while trying to run `docsify serve docs`, open powershell as an admin and run the following command:
```
Set-ExecutionPolicy bypass
```