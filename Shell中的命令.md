| 命令           | 功能                             |
| -------------- | -------------------------------- |
| pwd            | 打印当前所在位置                 |
| ls             | 列出当前文件夹内的内容           |
| mkdir <名字>   | 新建一个叫做 <名字> 文件夹       |
| cd <位置>      | 进入 <位置> 文件夹               |
| touch <文件名> | 创建一个文件名为 <文件名> 的文件 |
| oepn <文件名>  | 打开这个文件                     |
| rm <文件名>    | 删除一个文件                     |
| rm -r <文件夹> | 删除文件夹                                 |

```Bash
❯ pwd
/home/amibo/文档
❯ ls
20230906  教资  网页设计  Test  yr6095_y_r.layout.json
❯ mkdir justTest
❯ cd justTest
❯ touch index.html
❯ ls
index.html
❯ pwd
/home/amibo/文档/justTest
❯ open index.html #这一段看不懂没关系
❯ open index.html #同上
╭─░▒▓  │  ~/文档/justTest ▓▒░──────────────────────────░▒▓ ✔ │ 16:53:36  ▓▒░
╰─ Gtk-Message: 16:53:36.916: Not loading module "atk-bridge": The functionality is provided by GTK natively. Please try to not load it.
❯ 
❯ rm index.html #从这继续看
❯ cd .. #重点： ..代表上一级文件夹 在此例子中代表justTest文件夹的上层，也就是 文档
❯ rm -r justTest
❯ ls
20230906  教资  网页设计  Test  yr6095_y_r.layout.json

```