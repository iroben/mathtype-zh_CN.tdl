# MathType中文tdl
### 目前支持的中文范围是```\u4e00-\u9fa5```，可根据需要自己重新生成，生成规则`char/0x???? = "\unicode{0x????}";`

### 使用方法：
将`zh_CN(chars).tdl`复制到`MathType`安装目录下的`Translators`下，相应的导出格式tdl文件引入。
比如我要导出`AMSTeX`，那么就修改`AMSTeX.tdl`，添加 `include "zh_CN(chars).tdl";`
然后重启`MathTypeServer`就可以复制中文了
