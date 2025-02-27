## 简易使用手册

1. 根目录有个 hugo.exe , 在命令行中执行 `.\hugo.exe server` ，即可在本地预览；
2. theme 位于 themes/ 文件夹内，是一个 **git submodule** ；
3. 项目配置文件是 `hugo.toml`；
4. 图片文件位于 `static/img` ；
5. publications 配置，位于 `data/publications.yml`；
6. 首页内容为 `content/_index.md`
7. 自定义 scss 文件位于 `assets/css/_custom.scss`；

注意！不要直接改动 `themes/minimal-light` 主题文件中的文件。
每一次改动 `themes/minimal-light` 主题，都要上传 minimal-light 这个 submodule ，
然后再更新本项目。
