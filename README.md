<h1 align="center">Welcome to js-overlay 👋</h1>
<p>
  <a href="https://www.npmjs.com/package/js-overlay" target="_blank">
    <img alt="Version" src="https://img.shields.io/npm/v/js-overlay.svg">
  </a>
  <a href="#" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
  <a href="https://twitter.com/bastakotiujwol" target="_blank">
    <img alt="Twitter: bastakotiujwol" src="https://img.shields.io/twitter/follow/bastakotiujwol.svg?style=social" />
  </a>
</p>

> JS library that lets user to view image gallery, content, iframe content and ajax content in modal box

### 🏠 [Homepage](https://ujw0l.github.io/js-overlay)

### ✨ [Demo](https://ujw0l.github.io/js-overlay)

## Install

```sh
npm i js-overlay
```

## Script Tag 

```sh
Dowload and include following file:

js-overlay.js

```

## Initialization 

```sh
const overlay =  new jsOverlay();

For Content viewer 
overlay.createOverlay({ 
  elContent:'String', (String, content to be loaded in modal)
  containerHt: Number, (Number, Modal height.Default 500)
  containerWd: Number, (Number, Modal Width.Default 650)
  })

For Image viewer 
overlay.createOverlay({ 
  imgGallery:'seletor/s', (String, parent container selector/s of Image/s)
  containerHt: Number, (Number, Modal height.Default 500)
  containerWd: Number, (Number, Modal Width.Default 650)
  })

For Iframe viewer 
overlay.createOverlay({ 
  iframeUrl:'String', (String,  URL of page to be loaded)
  containerHt: Number, (Number, Modal height.Default 500)
  containerWd: Number, (Number, Modal Width.Default 650)
  })

For AJAX viewer 
overlay.createOverlay({ 
  ajaxUrl: 'String',(String, Url Where data to be sent and get reponse from ) 
  ajaxData: 'String',(String, Data to be sent to server) 
  ajaxMethod: 'String': (String,  GET or POSt method, default GET )
  containerHt: Number, (Number, Modal height.Default 500)
  containerWd: Number, (Number, Modal Width.Default 650)
  })  



```


## Author

👤 **UjW0L**

* Website: http://ujw0l.github.io
* Twitter: [@bastakotiujwol](https://twitter.com/bastakotiujwol)
* Github: [@UjW0L](https://github.com/UjW0L)
* LinkedIn: [@ujwol-bastakoti-2453a4169](https://linkedin.com/in/ujwol-bastakoti-2453a4169)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/ujw0l/js-overlay/issues). 

## Show your support

Give a ⭐️ if this project helped you!

<a href="https://www.patreon.com/UjW0L">
  <img src="https://c5.patreon.com/external/logo/become_a_patron_button@2x.png" width="160">
</a>

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_