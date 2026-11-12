# 文本桥 Windows 客户端分发

这是通用客户端的公开下载仓库，不包含配对凭据、服务端私密配置或工作项目资料。

从 [Releases](https://github.com/MidiAug/TextRelay-releases/releases/latest) 下载普通 ZIP，解压后运行 `TextRelay.exe`。远程助手显示 6 位码，在已授权个人电脑的文本桥页面核对并批准即可。首次配置后后台自动同步纯文本，无需逐次点击。

配对请求 5 分钟有效，六位码不能直接访问剪贴板。配置经过临时 RSA-OAEP-SHA256 和认证加密传递，设备凭证由当前 Windows 用户的 DPAPI 保护。程序提供托盘暂停、退出及连接状态。

自建二进制尚无 Authenticode 签名。程序不调用 PowerShell、不修改执行策略或设备安全设置；设备自身的下载与应用控制仍然适用。请只批准自己发起的配对，安装后重新复制新的纯文本进行验收。

GitHub 只分发程序，剪贴板不通过 GitHub 传输。未完成所有受管 Windows 环境的运行验证，也未做独立安全审计。每个发行版附有 SHA-256 校验文件。
