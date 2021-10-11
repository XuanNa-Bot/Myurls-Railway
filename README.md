# Myurls-Railway

在 [Railway](https://railway.app/) 上运行 [Myurls](https://github.com/CareyWang/MyUrls) 短网址程序

## Installation

### 部署

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https%3A%2F%2Fgithub.com%2Fpzcn%2FMyurls-Railway&plugins=redis&envs=ENV_DOMAIN%2CENV_TTL%2CPORT&ENV_DOMAINDesc=Your+domain.&ENV_TTLDesc=Short+link+validity+period+%28day%29&PORTDesc=DO+NOT+CHANGE&ENV_TTLDefault=180&PORTDefault=80)

通过上方链接一键部署到Railway，并填入以下参数

参数说明：

- `DOMAIN` - 短链接域名，必填项，不需要添加https:// (如 abc.com)
- `TTL` - 短链接有效期，单位(天)，默认180天 (default 180)
- `PORT` - 端口，保持80，请勿修改

### 添加域名

在Cloudflare中添加域名，并配置SSL/TLS为完全及以上，并在Railway中接入该域名，参考[官方文档](https://docs.railway.app/deploy/exposing-your-app#lets-encrypt-ssl-certificates)。

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)