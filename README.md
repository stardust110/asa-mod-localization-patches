# ASA 模组汉化补丁

这是方舟生存飞升（ARK: Survival Ascended）模组汉化补丁的发布仓库。
大体积汉化包只作为 GitHub Release 附件发布，仓库 Git 历史不保存游戏文件、模组原包或本机路径。

## 下载与安装

请在 [Releases](../../releases) 下载同一版本的以下二选一文件：

- `模组汉化包_版本.zip`：正常中文汉化，物品名称和说明显示中文。
- `模组（物品双语）汉化包_版本.zip`：物品名称和说明显示英文原文并附中文。

安装步骤：

1. 关闭游戏。
2. 将所选 ZIP 内的全部文件解压到游戏目录的 `ShooterGame\Content\Paks`。
3. 使用当前版本的 `pakchunk9999-Windows_P.pak`，不要同时放置旧版本汉化包。
4. 字体放大补丁单独安装。字体补丁和官方 PDF 说明放在 Release 附件说明的字体补丁文件夹中，不能用它替代模组汉化包。

## 支持与来源

补丁按 `zh / ja / de` 语言回退路径生成；中文译文在选择日语或德语界面时仍可显示。

官方汉化补丁来源：[飞书官方汉化补丁页面](https://my.feishu.cn/wiki/ZipZwbSwZipThMkiFrHcibeCn6e)。

反馈问题时，请附上模组 ID、游戏语言、补丁版本、出问题的界面截图和复现步骤，提交到仓库 Issues。

## 文件校验

每个 Release 附带 `SHA256SUMS.txt`。下载后可在 PowerShell 中运行：

```powershell
Get-FileHash .\模组汉化包_版本.zip -Algorithm SHA256
```

本仓库不收录大 ZIP；请始终从 Release 页面下载，避免拿到旧的测试包。
