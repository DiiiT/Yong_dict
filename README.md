# Yong_dict
小小输入法自制词库
## 词库说明
 med.txt=西医词库
 tcm.txt=中医词库
 net.txt=qq输入法词库_网络流行用语（见http://dict.qq.pinyin.cn/dict_detail?dict_id=39）
 simp.txt=Rime【袖珍簡化字拼音】輸入方案(见https://github.com/rime/rime-pinyin-simp)
## 词库转化
### 准备工具
* 深蓝词库转换工具：https://github.com/studyzy/imewlconverter/releases
* WPS或MS OFFICE
* 文本编辑器
* 下载对应词库

### 步骤
* 深蓝词库转换为“小小输入法词库”，支持多词库合并。
* 如需合并相同词条可将转换完毕的“小小输入法词库”转化为“自定义”（表1），将转化完毕的词库保存为txt格式
* WPS或MS OFFICE导入txt文件
 * 打开电子表格（以WPS为例）
 * 选择“数据”选项卡，点击“导入数据”，分隔符号选择“Tab”
 * 选择A列、B列，选择“数据”选项卡，点击“删除重复数据”
 * 将数据复制到文本编辑器并保存
 * 通过深蓝词库将“自定义”转换为“小小输入法词库”（表2）并保存为txt格式
* 将txt文件放入小小输入法程序目录下，具体位置为yong\mb，可存放入子文件夹中，例如yong\mb\dict
* 小小输入法设置，选择“拼音”，填入txt文件地址，以输入法程序文件夹作为当前文件，注意win下将反斜杠写为斜杠，多个词库用西文空格间隔，以词频排序。例：
 * mb/dict/simp.txt mb/dict/net.txt mb/dict/tcm.txt mb/dict/med.txt
* 保存后重启输入法

###### 表1：
|      格式设置  |               |       |
| ------------- |:-------------:| -----:|
|               |词条排序        |每个编码之间的分隔符： 无 |
|[√]包含编码     |编码： 1        | [ ]编码前带分隔符  [ ]编码后带分隔符 |
|               | 汉字： 2       | 编码汉字词频之间的分隔符：  Tab |
|[ ]包含词频     |词频：          | 换行符：  \r\n |
* 表1：去掉默认选择的“包含词频”，将“分隔符”改为"Tab"

 
###### 表2：
格式设置  |          |
-------- | -------- |---------
          |词条排序  |每个编码之间的分隔符： 无
[√]包含编码|编码： 1  | [ ]编码前带分隔符  [ ]编码后带分隔符
          | 汉字： 2 | 编码汉字词频之间的分隔符：  Tab
[ ]包含词频|词频：    | 换行符：  \r\n
* 表2：去掉默认选择的“包含词频”，将“分隔符”改为"Tab"
