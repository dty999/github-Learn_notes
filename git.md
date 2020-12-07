# git使用

1. 安装,一路next,选择默认编辑器为vscode

2. 配置用户
    >打开 Git Bash Here 输入下面命令  
    >git config --global user.name "myname" **global表示电脑当前用户,还有其他可选值:system等**
    >git config --global user.email xxxx@aliun.com
    >git config --list  

## 概念和名词解释

- 执行git init 就会在当前文件夹下产生一个.git文件夹,这个文件夹可以理解为仓库,其中目录对应功能如下:

| 目录或文件名  | 作用  |
| :----------| :----  |
| hooks | 包含客户端或服务端的钩子脚本 |
| objects | 存储所有数据内容 |
| info | 包含一个全局性排除文件 **意思就是哪些文件不需要管理了就放里面** |
| logs | 使用git时产生的日志信息 |
| objects | 存储所有数据 |
| refs | 跟分支有关 |
| config | 文件包含项目特有的配置选项 |
| HEAD | 文件指出目前被检出的分支 |
| index | 文件保存暂存区信息 |

- linux基础命令
| 命令 | 作用 |
| :---- | :----- |
| clear | 清除屏幕 |
| ll | 显示当前文件夹下文件和目录 |
| find path | 列出path下文件夹和子孙文件夹 |

- git对象:key-value组成的对象,是一个blob类型  

## 高级命令

  1. git init

  2. git add ./ 命令

  3. git commit -m "注释"

  4. git status

  5. git diff  

  6. git reset --hard HEAD commit_id

  7. git log

  8. git reflog

  9. git reset --hard commit_id  
