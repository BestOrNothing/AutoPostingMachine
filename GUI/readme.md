##GUI程序放在这个文件夹下

###9月5日修改
 1. 密码输入框密文显示
 1. 增加验证码图片元素输入框，获取输入框文本函数--getcaptchapicelement;
 1. 增加验证码输入元素输入框，获取输入框文本函数--getcaptchainputelement.

###9月9日修改
 1. 将按钮输入元素输入框重命名为提交请求的url，get函数重命名为--getrequesturl.

###9月12日修改
 1. 修改了“自动登录”和“记住密码”按钮不能复选的bug
 1. 增加了六个输入框，get函数分别为
    1. 账号输入元素：getaccountinputelement;
    2. 密码输入元素：getpasswordinputelement;
    3. 验证码输入框元素： getvericodeinputelement;
    4. 验证码图片元素：getvericodepicelement;
    5. 提交请求的url：getpostrequesturl;
    6. 登录页面的url：getloginurl.
