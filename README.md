### 注意 ⛔

这个代理列表是从互联网上可用的免费代理中收集的。它们仅在此仓库中显示以便于访问。我不对这些代理负任何法律责任。

### 捐赠 💸
- [蓝绿赞助器](https://lucksss.com)

### HTTPS 代理示例

###### 在 Linux 上运行 Curl
```console
curl --proxy-insecure -k --proxy 'https://xxx.xxx.xxx.xxx:xxxx' -o - https://ip.lucksss.com/
```

###### 在 Windows 上使用干净配置文件运行 Chrome 浏览器
```console
"C:\Program Files\Google\Chrome\Application\chrome.exe" --ignore-certificate-errors --ignore-ssl-errorsrs --proxy-server="https://xxx.xxx.xxx.xxx:xxxx" --user-data-dir="%TEMP%\chrprofile1" "https://ip.lucksss.com/"
```

#### CONNECT 代理示例
###### 在 Linux 上运行 Curl
```console
curl --proxytunnel -k --proxy 'http://xxx.xxx.xxx.xxx:xxxx' -o - https://ip.lucksss.com/
```

### 代理链接

  - **HTTP**
    ```bash
    https://raw.githubusercontent.com/TryHarder-L/proxyList/master/http.txt
    ```
  - **SOCKS4**
    ```bash
    https://raw.githubusercontent.com/TryHarder-L/proxyList/master/socks4.txt
    ```
  - **SOCKS5**
    ```bash
    https://raw.githubusercontent.com/TryHarder-L/proxyList/master/socks5.txt
    ```
