# collect-exports

[![NPM version](https://img.shields.io/npm/v/collect-exports?color=a1b858&label=)](https://www.npmjs.com/package/collect-exports)

## Sponsors

## use

### runtime(ESM, CJS)

**ESM**
```javascript
const exports =  await getExportsRuntime("vue");

exports === ["ref", "KeepAlive", ...]
```
**CJS**
```javascript
const exports =  await getExportsRuntime("react");

exports === ["Children","Component","Fragment","Profiler","PureComponent",...];
```
### static (ESM, CJS)
```javascript
const exports = await getExportsStatic("vue");

exports === ["ref", "KeepAlive", ...]
```



**本插件是根据anthony Fu的视频实现， 本插件只为自己记录用**
###
[视频地址](https://www.bilibili.com/video/BV1Z34y1H7fJ?spm_id_from=333.999.0.0)
###
[源包地址](https://www.npmjs.com/package/pkg-exports)

## License

[MIT](./LICENSE) License © 2022 [daly-dai](https://github.com/daly-dai)
