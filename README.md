### Errors

===========================================================

    ReferenceError: cmpos is not defined
    at Function.relogin (order.js:10011)
    at order.js:10622
    at <anonymous>

===========================================================

    ERROR in chunk checkInfo [entry]
    js/[name].[chunkhash:5].js
    Cannot use [chunkhash] for chunk in 'js/[name].[chunkhash:5].js' (use [hash] instead)

解决方法：
plugins里面的热替换插件（hotModuleReplacementPlugin）注释掉
