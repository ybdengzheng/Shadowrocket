### 懒人必备，开箱即用；<br>
### 自动分组，快捷分流；<br>

#### Rules.conf - 配置介绍
##### 配置功能介绍：<br>
具有强大的广告拦截功能；<br>
具有有效的防追踪/劫持功能；<br>
ChatGPT等AI工具单独分流；<br>
WeChat/Telegram单独分流，规避因配置变化导致的封号风险；<br>
Apple/Microsoft/Goole单独分流；<br>
国内地址/国际地址，国内媒体/国际媒体，可单独分流；<br>
使用加密的DoH，防止DNS泄露，并有效屏蔽未加密的DNS查询；<br>
完善的规则，配合Shadowrocket的配置自动更新，一次操作，无须后续操作；<br>

##### 使用必看：<br>
你所使用的节点，必须包含<美国节点>，<新加坡节点>；<br>
如不包含这两地区节点，则需要自行修改正则；<br>
本策略默认指定Telegram使用<新加坡节点>，其他规则使用<美国节点>；<br>

##### 使用办法：<br>
打开Shadowrocket，点击[配置]，点击左上角的[扫描]，识别下方的二维码，应用即可；<br>
如无法加载配置，请切换至[代理]模式，或自行检查网络；<br>

##### 分流办法：<br>
打开Shadowrocket首页，下拉，选择你想要修改的分流，选择策略即可；<br>
为了保证完整的接管流量，本策略默认使用<美国优先>兜底；<br>

##### 规则地址：<br>
https://raw.githubusercontent.com/XiangwanGuan/Shadowrocket/main/Rules.conf<br>
![qrcode](https://github.com/user-attachments/assets/faf02085-0828-430c-8509-fb09ffb7287f)

#### RulesLite.conf - 配置介绍
##### 配置功能介绍：<br>
基于Rules.conf修改，除不包含策略组以外，其余配置完全相同；<br>

##### 规则地址：<br>
https://raw.githubusercontent.com/XiangwanGuan/Shadowrocket/main/RulesLite.conf<br>
![qrcode_raw githubusercontent com](https://github.com/user-attachments/assets/871c0452-5483-4059-b3bf-c66e039d2c2b)

#### 本策略依赖如下项目：<br>
https://github.com/blackmatrix7/ios_rule_script/blob/master/rule/Shadowrocket<br>

#### 鸣谢：<br>
@blackmatrix7
