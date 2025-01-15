文件说明：

一、Clash-Full.ini是分流规则设置文件，在机场配置中采用自定义配置

二、Clash-Dev是openClash-插件设置-开发者选项中的替代内容，用于去广告

三、openClash.txt是openClash的插件配置文件，用于替换路由器中自带的etc-config-openClash文件，替换后注意清除.txt后缀。

四、订阅地址转换Docker指令（20241123更新：支持HY2节点）：  
docker run --name=SubConverter -d --restart=always -p 25500:25500 asdlokj1qpi23/subconverter:lates
