# golang 调用腾讯云人脸识别API
	/**
	* 通过图片url调用api
	* appid  
	* mode
	* imageUrl 图片路径
	* sessionId
	* sessionKey
	* url 请求路径
	*/
	t := NewTencentAPI(appid,mode,sessionId,sessionKey,url)
	result := t.PostByUrl(imageUrl)
