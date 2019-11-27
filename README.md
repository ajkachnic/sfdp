<h1 align="center">Welcome to sfdp 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-0.0.1-blue.svg?cacheSeconds=2592000" />
  <a href="#" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
  <a href="https://twitter.com/AndrewKachnic" target="_blank">
    <img alt="Twitter: AndrewKachnic" src="https://img.shields.io/twitter/follow/AndrewKachnic.svg?style=social" />
  </a>
</p>

> Secure File Deleletion Protocol. A tool to delete files securely. The tool encrypts the target file with AES256 using cryptographically secure random keys. This encryption happens twice by default but can be specified. Following this encryption, the checksum of this file is computed and replaces the actaual file. After all of this, the file is deleted with a selected number of passes. This takes awhile.

## Install

```sh
go get https://github.com/ajkachnic/sfdp.git
```

## Author

👤 **Andrew Kachnic**

* Website: ajkachnic.github.io
* Twitter: [@AndrewKachnic](https://twitter.com/AndrewKachnic)
* Github: [@ajkachnic](https://github.com/ajkachnic)

## Show your support

Give a ⭐️ if this project helped you!

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_