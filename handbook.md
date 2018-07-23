## 1.npm script命令
```
npm install
# 启动项目
npm run dev 
# 打包js
npm run build:spui
# 打包css
npm run build:spui-css
```

## 2.发布打包，文件说明

### 执行`npm run build:spui`命令后examples/dist目录下
```
.examples
    ├──dist
            ├──index.html                        pc官网入口
            ├──mobile.html                       移动端入口
            ├──manifest.min.hash.js
            ├──spui-mobile.hash.css              移动端css
            ├──spui-mobile.min.hash.js           移动端js
            ├──spui.hash.css                     pc官网css
            ├──spui.min.hash.js                  pc官网js
            └──vendor.min.hash.js
```
### 执行`npm run build:spui`命令后lib目录下
```
.lib
  ├──spui.js
```
### 分包css，执行`npm run build:spui-css`命令后lib/spui-css目录下
```
.lib
    ├──spui-css
            ├──index.css                    
            └──world.css
```