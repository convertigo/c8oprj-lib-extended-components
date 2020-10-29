# lib_ExtendedComponents

Set of shared components you can use in your projects:
    
    - agGrid : Display & Edit tabular data
    - ngxTagInput : Display / remove Chips tags in input fields
    - angularxQRCode : QR Code component/module library to generate QR Codes (Quick Response)

SharedComponent can be dropped (CTRL + mouse click) in Mobile Builder page components to make use of it.

## agGrid

The **agGrid** SharedComponent is based on **ag-grid-community** and **ag-grid-angular** NPM packages.\
Visit [Angular Grid](https://www.ag-grid.com/angular-grid/) for documentation and usage.\
See it in action in **testAgGrid1** and **testAgGrid2** Mobile Builder pages.

![agGrid screenshot 1](./doc/images/ConvertigoStudio_agGrid.png)

## ngxTagInput

The **ngxTagInput** SharedComponent is based on **ngx-chips** NPM package.\
Visit [Tag Input Component](https://github.com/Gbuomprisco/ngx-chips/#readme) for documentation and usage.\
See it in action in **testNgxInput** and **testNgxInput1** Mobile Builder pages.

![ngxTagInput screenshot 1](./doc/images/ConvertigoStudio_ngxTagInput.png)

## angularxQRCode

**angularxQRCode** shared component is base on **angularx-qrcode** package version 1.6.4\
**angularx-qrcode** is a Ionic 3 and Angular4+ QR Code component/module library to generate QR Codes (Quick Response) in your Ionic and Angular 4+ app with support for AOT. It is a drop-in replacement for the no-longer-maintained angular2 component ng2-qrcode and based on qrcodejs.

### Parameters

| Attribute        | Type           | Default | Description  |
| ------------- |-------------| -----|------------|
| allowEmptyString      | Boolean | false     | Allow empty string |
| colorlight      | String | '#ffffff'     | Dark color |
| colordark      | String | '#000000'     | Light Color |
| level | String | 'M'    | QR Correction level ('L', 'M', 'Q', 'H') |
| qrdata      | String | '' | String to encode |
| size      | Number | 256     | Height / Width (any value) |
| usesvg      | Boolean | false     | SVG Output |