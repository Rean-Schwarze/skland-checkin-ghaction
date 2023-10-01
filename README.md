# skland-checkin-ghaction

利用 GitHub Action 自动完成森空岛签到，基于[Maojuan-lang](https://github.com/Maojuan-lang/SenKongDao)的实现包装。

## How to use
1. 进入自己仓库的项目主页后，在上方的菜单中进入Settings > Secrets and variables > Actions

2. 点击 New repository secret

3. 创建名为`TOKEN`的环境变量（注意变量名全大写），并填入你的鹰角网络通行证，如果要管理多个账号，换行即可

4. 如果是第一次使用GitHub Action的话，还需要手动打开这个功能 在你仓库上方菜单中进入Actions

5. 点击 I understand... enable them > Enable workflow

6. 之后就可以自动运行签到了, 想要手动测试的话，选择左侧的Auto Sign > Run workflow, 刷新页面就能看到结果了
