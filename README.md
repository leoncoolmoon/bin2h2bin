# bin2h2bin
array to file to arry
## 功能说明
这个纯静态网页实现了以下功能：
二进制文件转C/C++头文件：
用户上传任意二进制文件
转换为包含十六进制数组的.h头文件
自动生成符合C/C++语法的数组定义
每行显示16个字节，格式整洁
头文件转二进制文件：
用户上传.h头文件
解析头文件中的十六进制数组（支持 0x12 或十进制 18 格式）
将数组数据转换回原始二进制文件
自动检测并处理无效数据
用户界面特点：
标签页切换两种转换模式
文件拖放或点击选择
显示文件大小信息
转换结果即时下载
错误提示和验证
响应式设计，适配不同设备

隐私保护：

所有处理在浏览器中完成

文件不会上传到服务器

无数据泄露风险
