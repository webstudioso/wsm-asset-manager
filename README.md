 # Webstudio Asset Manager

This module enable the upload of file based assets (images, multimedia, etc) to IPFS [Webstudio](https://webstudio.so)

 ![Webstudio Asset Manager](https://github.com/webstudioso/wsm-asset-manager/actions/workflows/production.yml/badge.svg)

### Testing and Building Module
```
npm i
npm run test
npm run build
```

### Publish to NPMJS
```
npm publish
```

### Importing Dependency in Webstudio
Add it to the project, this is compatible with `grapesjs` as well.
```shell
npm i --save wsm-asset-manager@latest
```
To import in the editor add the file and include it as a Plugin
```js
import { AssetManager as assetManager } from "wsm-asset-manager";

const editor = grapesjs.init({
    container: "#gjs",
    assetManager
})
```