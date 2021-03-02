# composer_demo

## 安装

```
composer require ledaishu/mydemo
```

## 示例

新建文件`index.php`

```
<?php
// 加载自动加载文件
require_once './vendor/autoload.php'; 

use Flower\Rose;
use Flower\Lily;

$rose = new Rose();
$lily = new Lily();

echo $rose->desc();
echo "\n";
echo $lily->desc();
```

## 执行

在命令行执行`php index.php`，输出结果：

```
this is rose flower
this is lily flower
```

