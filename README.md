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


