react抛开nodejs，如何去使用它，这里需要的是引入3个js文件,这三个最新的代码去他们官网寻找
```javascript
<script src="https://unpkg.com/react@15/dist/react.js"></script>
<script src="https://unpkg.com/react-dom@15/dist/react-dom.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/babel-core/5.8.34/browser.min.js"></script>
```
代码的语法，则不完全是javascript语法，代码需要设定为babel类型的脚本
```javascript
<script type="text/babel">
   //代码
</script>
<script type="text/babel" src="jsx文件"></script>
```
