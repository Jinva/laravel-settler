# Laravel Settler

在 `laravel/homestead` 的基础上，增加了：

- 默认安装 heroku 命令
- 国内 Composer 加速
- cnpm 国内 npm 加速
- 默认安装 Elasticsearch

## 原理

基于 [laravel/homestead](https://app.vagrantup.com/laravel/boxes/homestead) 构建自定义的 BOX。

## 教程

1. 检查 `vagrant box list` 是否有 `laravel/homestead`;
2. 如果有需要的话，修改 `provision.sh` 并确定无误，这个脚本将会在新的 Box 里运行，请利用此脚本来定制软件和配置；
3. 运行 `./build.sh` 生成定制的 box。
