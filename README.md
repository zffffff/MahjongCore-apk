# MahjongCore-apk

Public **CI relay** for 《电子基盘》(`mjelctrn`) debug APK.

- Source stays private: [`zffffff/MahjongCore`](https://github.com/zffffff/MahjongCore)
- This repo only runs Actions and hosts a short-lived APK artifact

## Build

1. Open [Actions → Android mjelctrn APK](https://github.com/zffffff/MahjongCore-apk/actions)
2. **Run workflow**（可选填私仓 `ref`，默认 `main`）
3. Download artifact `mahjongcore-mjelctrn-apk`
4. 安装后请 **删除** 该 artifact（APK 内含商业 ROM，勿长期挂公开页）

## Secret

| Name | Purpose |
|------|---------|
| `MAHJONGCORE_DEPLOY_KEY` | 私仓 `MahjongCore` 的只读 Deploy Key（SSH） |

Forks 不会带上此 Secret。
