# :space_invader: QRCode Component

> :space_invader: QRCode component made easy with web components.

## How to install and use

1 - Install the element using [Bower](http://bower.io/):

```sh
bower install qrcode-component --save
```

2 -  Import the element:

```html
<link rel="import" href="bower_components/qrcode-component/qrcode-component.html">
```

3 - Start using it!
```html
<qrcode-component url="https://felipesousa.github.io/"></qrcode-component>
```

## Properties

Property  | Type        | Default   | Description
:---      |:---         |:---       |:---
`url`    | *String*    | `yoursite.com`       | URL reference to QRCODE.

## Styling

The following custom properties and mixins are available for styling:

Custom property             | Default  | Description
:---                        |:---      |:---
--qrcode-component-width | 150px | QRCODE area 

## Browser Support

Using the [webcomponents.js](https://github.com/WebComponents/webcomponentsjs):

 ![Chrome](https://cdnjs.cloudflare.com/ajax/libs/browser-logos/39.2.2/chrome/chrome_48x48.png) | ![Opera](https://cdnjs.cloudflare.com/ajax/libs/browser-logos/39.2.2/opera/opera_48x48.png) | ![Firefox](https://cdnjs.cloudflare.com/ajax/libs/browser-logos/39.2.2/firefox/firefox_48x48.png) | ![Safari](https://cdnjs.cloudflare.com/ajax/libs/browser-logos/39.2.2/safari/safari_48x48.png) |![IE](https://cdnjs.cloudflare.com/ajax/libs/browser-logos/39.2.2/archive/internet-explorer_9-11/internet-explorer_9-11_48x48.png) |  ![Edge](https://cdnjs.cloudflare.com/ajax/libs/browser-logos/39.2.2/edge/edge_48x48.png) |
:---: | :---: | :---: | :---: | :---: | :---: |
Latest ✔ | Latest ✔ | Latest ✔ | Latest ✔ | 🚫 | Latest ✔

## Development

1 - Install [Bower](http://bower.io/) & [Polymer-CLI](https://www.polymer-project.org/1.0/docs/tools/polymer-cli):

```sh
npm install -g bower polymer-cli
```

2 - Install local dependencies:

```sh
bower install
```

3 - Start the development server:

```sh
polymer serve --open
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

[MIT License](https://github.com/felipesousa/qrcode-component/blob/master/LICENSE) © [Felipe Sousa](https://felipesousa.github.io/)

