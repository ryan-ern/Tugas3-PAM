# HILING.ID (MAKE YOUR FLIGHT EASIER!)

---
#### Screenshot Landing Page Aplikasi
<p align="center">
    <img width="200px" src="/assets/SS_Tampilan1.jpg">
</p>

#### Screenshot Hasil Pencarian Aplikasi
<p align="center">
    <img width="200px" src="/assets/SS_Tampilan2.jpg">
</p>

## Repo Structure
```
/                   # All assets, components, db, and screen. Also routes
├─ assets/          # Dummy or images and video
├─ components/      # All components
│  └─ index.js      # Routing every components 
├─ datas/           # Currently dummy data with JSON type 
│  └─ index.js      # Work as third layer route and make it into component 
│
├─ App.js            # Main js to be rendered, 
                       cause only CLI that appear index.js at root folder 
```

## Requirements
- [React native](https://reactnative.dev/)
- [React native vector icon by MaterialComunityIcons](https://materialdesignicons.com/)
- [Expo](https://expo.dev/)


## Installation
Run the following command below in project terminal root to build android apk
```
yarn install
```
or
```
npm install
```
&nbsp;
Next is run the same function as git init inside expo
```
npx expo install expo-updates
```
&nbsp;
Build inside expo
```
expo build:android
```
or
```
npm install -g eas-cli
eas build -p android
```
&nbsp;
Then wait and follow the instruction if it the first build, generate a new key and choose apk.Last if expo need login in terminal input same as your expo.dev account
&nbsp;

