# uchttp
http请求操作库

raw + json 请求
uchttp.Request(method string, requrl string, body io.Reader)

method：GET、POST
requrl：请求的url
boby：请求参数，json结构

form请求 
uchttp.RequestForm(method string, requrl string, body io.Reader)
method：GET、POST
requrl：请求的url
