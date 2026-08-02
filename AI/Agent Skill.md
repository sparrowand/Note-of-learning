一般为markdown格式。
作为头部的部分，name和description为metadata（元数据）
name为skill的名称。description为向ai描述这个agent skill

第二部则解释ai需要遵守的规则。

# reference
可以在特定情况下的特定情况触发。
可以在skill的规则中添加为`仅在提到xxx时触发，需读取该reference文件`

# 渐进式披露
ai为渐进式披露，第一层为元数据层，相当于目录，始终加载。如名称与描述。
第二层是指令层，以便为skill，按照需求加载。
第三层为指令层，有reference和script。如脚本。在指令层的基础上增加了一层按需加载。

# 推荐
https://github.com/mattpocock/skills