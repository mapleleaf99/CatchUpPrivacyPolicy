# CatchUp 隐私政策（App Store）

结构参考：`Afterwise_iOS/afterwisePrivacyPolicy`（GitHub Pages + `/docs`）。

## 本地预览

打开 `docs/index.html` 即可预览中英切换。

## 发布到 GitHub Pages

1. 将本仓库（或仅 `privacyPolicy` 内容）推到 GitHub  
2. Settings → Pages → Deploy from a branch → `main` / `/docs`  
   - 若仓库根目录就是本文件夹，选 `/docs`  
   - 若整仓是 CatchUp App，可把 `privacyPolicy` 单独建成 `CatchUp-privacy` 仓库，并把 `docs` 放在该仓根下的 `docs/`  
3. 启用后地址一般为：

```text
https://<你的GitHub用户名>.github.io/<仓库名>/
```

4. 把下面 App 内常量改成真实地址：

`CatchUp/Utilities/LegalLinks.swift` → `privacyPolicyURL` / `termsOfUseURL`

## App Store Connect

「App 隐私」与审核信息里的 Privacy Policy URL 填同一地址。

联系邮箱：`guofeifeng9@gmail.com`
# CatchUpPrivacyPolicy
