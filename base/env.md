## 运行环境
- Linux 系统 (Swoole 不支持在 Windows 上运行)
- [PHP](https://php.net/) >= 7.0
- [Composer](https://getcomposer.org/)
- [Swoole](https://www.swoole.com/) >= 2.2.0 (必须启用协程，如使用 Redis 请开启)
- [Hiredis](https://github.com/redis/hiredis/releases) (需要在安装 Swoole 之前装)
- Redis、PDO 扩展 (如有需要在异步任务 task 中操作对应数据库，则必须安装)

## Windows 开发者

可以使用虚拟机、Windows 10 Linux 子系统等环境，实现在 Windows 系统上开发和调试。