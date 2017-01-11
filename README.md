### 安装

```
composer require scolib/think-monolog:dev-master
```

### 使用

安装完成后, 就可以立即在应用的代码中这样使用 monolog:

```
\Sco\Think\Logger::debug('这是一条debug日志');
\Sco\Think\Logger::info('这是一条info日志');
\Sco\Think\Logger::warn('这是一条warn日志');
\Sco\Think\Logger::error('这是一条error日志');
```

