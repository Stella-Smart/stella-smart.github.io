### 升级步骤
1. 更新ota_info.json 中的信息,确保 `ota-info.json`中的版本号 和 待升级的ota 文件版本一致
2. 替换`ble_uart_server.bin`文件

#### 关于如何将文件下载下来,完成上面操作,并上传,下面提供一个思路
```shell
git clone https://github.com/Stella-Smart/stella-smart.github.io.git
cd stella-smart.github.io
# 按照 升级步骤 中的描述,完成相关操作
git commit -m "update ota 1.0.1" -a
git push origin main
> input Username: Stella-Smart
> input Passowrd: <这里输入github 生成的token>#在settings > Developer setttings > Personal access tokens 找到它
```