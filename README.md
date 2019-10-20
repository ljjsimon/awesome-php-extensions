# Awesome PHP extensions
收集 PHP 扩展

# Contributing
欢迎PR

# The list
## 数据转换
- [ds](https://github.com/php-ds/extension) - 标准数据结构
- [php-ext-excel-export](https://github.com/viest/php-ext-excel-export) - 输出 Excel 格式
- [php-ext-trie-filter](https://github.com/wulijun/php-ext-trie-filter) - trie 查找树，用于文本匹配
- [php-ext-collection](https://github.com/viest/php-ext-collection) - 数组数据操作
- [php-rapidjson](https://github.com/rustjason/php-rapidjson) - 此库有问题
- [simdjson_php](https://github.com/crazyxman/simdjson_php) - simdjson 绑定，json 解析
- [php-decimal](https://github.com/php-decimal/extension) - 提供对 decimal 的支持。官方提供纯 php 版
- [php-toml](https://github.com/shukean/php-toml) - 解析 toml 文件
- [igbinary](https://github.com/igbinary/igbinary) - 替代 serialize 和 unserialize
- [php-ext-jq](https://github.com/kjdev/php-ext-jq) - 封装 jq ，快速查找 json

## 客户端
- [phpredis](https://github.com/phpredis/phpredis) - Redis 客户端
- [phpiredis](https://github.com/nrk/phpiredis) - 封装了 Hiredis 的 Redis 客户端
- [msphpsql](https://github.com/Microsoft/msphpsql) - 微软出的 SQL Server 客户端
- [php-rdkafka](https://github.com/arnaud-lb/php-rdkafka) - kafka 客户端
- [arangodb-php-driver](https://github.com/sandrokeil/arangodb-php-driver) - ArangoDB 客户端
- [PHP-FoundationDB](https://github.com/viest/PHP-FoundationDB) - FoundationDB 客户端

## 网站框架
- [yar](https://github.com/laruence/yar) - RPC框架
- [yaf](https://github.com/laruence/yaf) - 网站框架
- [cphalcon](https://github.com/phalcon/cphalcon) - 网站框架
- [asf](https://github.com/yulonghu/asf) - 网站框架
- [ice](https://github.com/ice) - 用 Zephir 写的框架
- [CSpeed](https://github.com/liqiongfan/cspeed) - 网站框架

## 框架组件
- [SeasLog](https://github.com/SeasX/SeasLog) - 日志
- [Pimple](https://github.com/silexphp/Pimple) - 依赖注入
- [yaconf](https://github.com/laruence/yaconf) - 配置管理
- [php-mustache](https://github.com/jbboehr/php-mustache) - mustache 解析库

## 异步
- [swoole](https://github.com/swoole/swoole-src) - 多进程框架
- [pthreads](https://github.com/krakjoe/pthreads) - 多线程
- [zan](https://github.com/youzan/zan) - 有赞出的异步网络库
- [php-ion](https://github.com/php-ion/php-ion) - 异步执行库
- [event](https://bitbucket.org/osmanov/pecl-event) - 进程间通信
- [parallel](https://github.com/krakjoe/parallel) - 并行运算

## 代码分析
- [XHProf](https://github.com/phacility/xhprof) - 性能分析工具
- [Molten](https://github.com/chuan-yun/Molten) - 应用透明链路追踪工具
- [XDebug](https://xdebug.org/) - PHP程序调试器
- [vld](https://github.com/derickr/vld) - 输出PHP脚本生成的中间代码
- [php-spx](https://github.com/NoiseByNorthwest/php-spx) - 自带后台界面的性能分析工具
- [php-memory-profiler](https://github.com/arnaud-lb/php-memory-profiler) - 函数内存使用分析工具
- [php-taint](https://github.com/laruence/taint) - XSS 代码检查
- [php-ast](https://github.com/nikic/php-ast) - AST 抽象语法树
- [php-spy](https://github.com/adsr/phpspy) - 性能分析工具
- [php-meminfo](https://github.com/BitOne/php-meminfo) - 内存分析工具

## 扩展编写
- [zephir](https://github.com/phalcon/zephir) - 用 PHP 编写 PHP 扩展
- [php-x](https://github.com/swoole/phpx) - cpp 开发
- [php-cpp](https://github.com/CopernicaMarketingSoftware/PHP-CPP) - cpp 开发
- [php-go](https://github.com/kitech/php-go) - 用 Go 语言编写 PHP 扩展
- [php-rc](https://github.com/rethinkphp/php-rs) - 用 Rust 语言编写 PHP 扩展

## 跨语言
- [ffi](https://github.com/dstogov/php-ffi) - 直接编译 c 语言代码
- [v8js](https://github.com/phpv8/v8js) - 用 V8 引擎执行 javascript
- [php-v8](https://github.com/phpv8/php-v8) - 用 V8 引擎执行 javascript
- [PHPython](https://github.com/bullsoft/PHPython) - 执行 python
- [php-python](https://github.com/jparise/php-python) - 运行 python 扩展
- [php-ext-wasm](https://github.com/wasmerio/php-ext-wasm) - 运行 WebAssembly
- [php-webview](https://github.com/siara-cc/php_webview) - 模仿浏览器运行 javascript，有 document

## 图片处理
- [php-smartcrop-extension](https://github.com/xymak/php-smartcrop-extension) - smartcrop 图片关键部位查找算法的 PHP 实现
- [php-vips](https://github.com/jcupitt/php-vips) - 图像处理库，封装 libvips
- [php-opencv](https://github.com/hihozhou/php-opencv) - opencv 客户端

## 字符串处理
- [php-akm](https://github.com/imaben/php-akm) - 文本查找
- [php_aho_corasick](https://github.com/ph4r05/php_aho_corasick) - Aho-Corasick 算法做字符串匹配
- [pinyin-php](https://github.com/duguying/pinyin-php) - 汉字转拼音
- [php-pinyin](https://github.com/bullsoft/php-pinyin) - 汉字转拼音
- [libsodium-php](https://github.com/jedisct1/libsodium-php) - 加密库，封装 libsodium

## 安全检查
- [taint](https://github.com/laruence/taint) - 检查XSS漏洞
- [xmark](https://github.com/fate0/xmark) - 检查多种漏洞

## 日志
- [php-yklogger](https://github.com/shukean/php-yklogger) - 记录日志

## 地理
- [geohash-php-extension](https://github.com/taogogo/geohash-php-extention) - 经纬度和 geohash 转换
- [geohash](https://github.com/shenzhe/geohash) - geohash
- [geospatial](https://github.com/php-geospatial/geospatial) - 包含一般的地理计算函数

## 其他
- [donkeyid](https://github.com/osgochina/donkeyid) - 64位自增id生成器
- [screw-plus](https://github.com/del-xiong/screw-plus) - 基于 screw 对 PHP 代码加密
- [mpl-php-extension](https://github.com/taogogo/mpl-php-extension) - 手机查找归属地
- [php-inotify](https://github.com/arnaud-lb/php-inotify) - 封装 inotify，监控文件状态
