本策略基于如下项目修改，源配置地址如下：

https://github.com/Johnshall/Shadowrocket-ADBlock-Rules-Forever/blob/release/lazy.conf
https://github.com/blackmatrix7/ios_rule_script/blob/master/rule/Shadowrocket/Advertising/Advertising.list

添加了屏蔽广告的策略：

RULE-SET,https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Advertising/Advertising.list,REJECT

移除了注释；
重新整理策略顺序；
