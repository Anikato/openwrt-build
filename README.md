# ImmortalWrt MT798x Auto Build

基于 [hanwckf/immortalwrt-mt798x](https://github.com/hanwckf/immortalwrt-mt798x) 的自动编译仓库。

## 支持设备

- H3C NX30Pro (MT7981)

## 特性

- 使用 GitHub Actions 云端自动编译
- 集成 [Passwall](https://github.com/Anikato/openwrt-passwall)（含 iptables-mod-socket 修复）
- 手动触发编译，固件自动上传到 Releases

## 使用方法

1. 进入 [Actions](../../actions) 页面
2. 选择 **Build ImmortalWrt MT798x** workflow
3. 点击 **Run workflow** 触发编译
4. 编译完成后在 [Releases](../../releases) 下载固件

## 自定义

- 修改 `configs/h3c_nx30pro.config` 调整编译选项
- 修改 `feeds.conf.default` 调整软件源
