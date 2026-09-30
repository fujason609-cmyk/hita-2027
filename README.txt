日田 · 壁外调查记录 2027 —— 独立版 

放到任何静态网站空间都能用，例如 GitHub Pages：
1. 在 GitHub 新建一个 public repo（例如 hita-2027）。
2. 把这个资料夹里的 5 个文件全部上传到 repo 根目录。
3. Settings → Pages → Source 选 main branch / root，保存。
4. 一两分钟后网址会是 https://你的帐号.github.io/hita-2027/
5. 把网址发给大家，用 Safari 打开，再按 分享 → 加入主画面。

打卡照片存在每个人自己的 iPhone（浏览器储存），不会上传到网络。
注意：iPhone 如果清除 Safari 网站资料，打卡照片会一起被删掉。

—— 让 Jason 上传照片、所有人都看得到（只有设定了金钥的手机能上传） ——
照片会存进这个 repo 的 photos 资料夹，网站会自动读取。
1. GitHub 右上角头像 → Settings → 最下面 Developer settings → Personal access tokens → Fine-grained tokens → Generate new token。
2. Token name 随便填（例如 hita-photos），Expiration 选旅行结束之后的日期。
3. Repository access 选 Only select repositories，选 hita-2027。
4. Permissions → Repository permissions → Contents 选 Read and write。
5. 按 Generate token，复制 github_pat_ 开头的那串字（只会显示一次）。
6. 在 iPhone 用 Safari 打开网站，拉到最下面「照片管理」，贴上后按保存。
之后每个地点会出现「上传打卡照片」和「加目的地照」。
金钥等于这个 repo 的写入钥匙，不要发给别人或贴到群组。
