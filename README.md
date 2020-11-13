``` bash
sudo bash < <(curl -Ls https://raw.githubusercontent.com/maomao1973/crack-soga-v2ray/master/install.sh)
```
 /etc/soga/soga.conf
ws 示例
示例：1.3.5.7;80;2;ws;;path=/v2ray|server=hk.domain.com|host=hk.domain.com
ws + tls 示例
示例：1.3.5.7;443;2;ws;tls;path=/v2ray|server=hk.domain.com|host=hk.domain.com
偏移端口 ws
示例：1.3.5.7;80;2;ws;;path=/v2ray|server=hk.domain.com|host=hk.domain.com|outside_port=34567
偏移端口 ws + tls
示例：1.3.5.7;443;2;ws;tls;path=/v2ray|server=hk.domain.com|host=hk.domain.com|outside_port=34567
