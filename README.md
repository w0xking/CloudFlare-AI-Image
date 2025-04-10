# CloudFlare-AI-image
基于Cloudflare Worker的AI图片生成脚本

-  "DS-8-CF": "@cf/lykon/dreamshaper-8-lcm"
-  "SD-XL-Bash-CF": "@cf/stabilityai/stable-diffusion-xl-base-1.0"
-  "SD-XL-Lightning-CF": "@cf/bytedance/stable-diffusion-xl-lightning"
-  "FLUX.1-Schnell-CF": "@cf/black-forest-labs/flux-1-schnell"
-  "SF-Kolors": "Kwai-Kolors/Kolors"
 
 五种可选文生图模型，默认SD-XL-Bash-CF，推荐FLUX.1-Schnell-CF 效果最好，但有每日使用限制

 部署该脚本需要绑定Workers AI，增加KV命名空间并绑定到IMAGE_KV。

 接口格式兼容openai，可在任意支持openai的客户端内使用。

 SF_TOKEN为硅基流动平台的api token，需要提前申请，不使用可不填写。

[![CloudFlare配置](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/01.png "")]([https://markdown.com.cn](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/01.png))
[![CloudFlare配置](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/02.png "")]([https://markdown.com.cn](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/02.png))
[![CloudFlare配置](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/03.png "")]([https://markdown.com.cn](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/03.png))
[![CloudFlare配置](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/04.png "")]([https://markdown.com.cn](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/04.png))
[![CloudFlare配置](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/05.png "")]([https://markdown.com.cn](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/05.png))
[![CloudFlare配置](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/06.png "")]([https://markdown.com.cn](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/06.png))
[![CloudFlare配置](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/07.png "")]([https://markdown.com.cn](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/07.png))
[![CloudFlare配置](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/08.png "")]([https://markdown.com.cn](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/08.png))
[![CloudFlare配置](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/09.png "")]([https://markdown.com.cn](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/09.png))
[![CloudFlare配置](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/10.png "")]([https://markdown.com.cn](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/10.png))
[![CloudFlare配置](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/11.png "")]([https://markdown.com.cn](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/11.png))
[![CloudFlare配置](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/12.png "")]([https://markdown.com.cn](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/12.png))
[![CloudFlare配置](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/13.png "")]([https://markdown.com.cn](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/13.png))
[![CloudFlare配置](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/14.png "")]([https://markdown.com.cn](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/14.png))
[![CloudFlare配置](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/15.png "")]([https://markdown.com.cn](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/15.png))
[![CloudFlare配置](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/16.png "")]([https://markdown.com.cn](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/16.png))
[![CloudFlare配置](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/17.png "")]([https://markdown.com.cn](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/17.png))
[![CloudFlare配置](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/18.png "")]([https://markdown.com.cn](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Image/refs/heads/main/example/18.png))