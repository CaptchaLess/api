##1.插件发送图片的格式
通过ajax发送GET请求，请求里面有相应验证码图片的URL，django里面可以通过`request.GET['url']`来获取相应的图片URL
 1. epc: `http://202.141.160.95:40001/captchaless/epc/?url=`
 2. yjs: `http://202.141.160.95:40001/captchaless/yjs/?url=`
 3. mis: `http://202.141.160.95:40001/captchaless/mis/?url=`
 4. weibo: `http://202.141.160.95:40001/captchaless/weibo/?url=`

##2. django以**HttpResponse**的形式发送识别后的字符串给插件，如“2345”

