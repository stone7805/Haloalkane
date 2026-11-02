# 卤代烃 · 四类通关 V2.0

可离线运行的单文件课堂网页游戏。`index.html` 已包含样式、题库和脚本，不需要安装依赖或构建。适配手机和电脑：小屏以横向关卡导航、纵向题卡和点选/输入完成操作，不依赖拖拽。

## 在 GitHub Pages 发布

1. 新建一个 GitHub 仓库，把本文件夹内的 `index.html` 和 `README.md` 上传到**仓库根目录**；不要把外层文件夹作为唯一根目录上传。
2. 打开仓库 **Settings → Pages**，在 **Build and deployment** 选择 **Deploy from a branch**，选择 `main` 和 `/(root)`，保存。
3. 等待 Pages 显示站点地址，将该地址发给学生。手机和电脑访问同一个网址即可；站点发布并不需要服务器程序。

可直接双击 `index.html` 在本机离线练习。GitHub 官方部署说明：[Configuring a publishing source for your GitHub Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)。

## 游戏规则

- 四关各 25 分，共 12 个小任务、满分 100 分：命名侦探、结构简式工厂、异构体工坊、证据鉴别室。
- 先输入班级、姓名和**10 位数字学号**并勾选核对；点击“锁定身份并开始”才启动本次活动。编号以点击时的设备本地时间、学号末两位和姓名拼音首字母组成。
- 完整作答才计一次正式提交；答错后继续核对，每多一次正式提交扣 2 分，单题最低保留该题满分的 60%。
- 正式答错的任务，**正式通过以后**还需独立重练正确。全部正式任务及必修错题完成后才开放成绩单与 A4 打印/PDF。
- 结构简式题接受明确表示连接关系的直链结构简式及反向写法；异构体题的多选项标有 A–F；鉴别题需要先按完整流程运行模拟，再判断证据能支持到哪一步。
- 实验是教学模拟，不是实际检验操作指南。颜色判读：AgCl 白色、AgBr 淡黄/奶油色、AgI 黄色；沉淀颜色不能单独确认完整碳骨架。

## 数据与设备

进度只保存在**当前浏览器的本地存储**。不同手机、电脑、浏览器、无痕窗口之间不会自动同步；GitHub Pages 静态站点也不会集中收集成绩。请在同一设备同一浏览器继续，并在通关后打印或另存 PDF 作为可移交记录。浏览器清理网站数据会删除本机进度；同一浏览器会话只对应一名学生。身份锁定与记录校验用于课堂流程约束，并不是防篡改的服务器认证。

如果已有异常记录，页面会提示并保护旧数据，不会默默覆盖。若教师决定重新开始，请先核对或留存旧记录，再清理该站点的浏览器数据。新版本使用独立存储键，不会覆盖旧版成绩。

## 文件与版本

- `index.html` — 完整网站及题库，V2.0；无外部运行时资源。
- `README.md` — 发布与教学使用说明。

课堂颜色及操作顺序参考：[Royal Society of Chemistry · Qualitative tests for organic functional groups](https://edu.rsc.org/download?ac=515967)、[Testing for negative ions](https://edu.rsc.org/experiments/testing-for-negative-ions/758.article)。
