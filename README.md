# v2rayN_custom_routing_rules
自定义v2rayN路由规则

一. 黑名单规则（默认规则为直连）：
    
    1. 对于玩 Steam 国区游戏，想要直连的用户，可以设置类别 geosite:steam@cn 为直连，意为将 steam 列表内所有被标记了 @cn attribute 的规则（域名）设置为直连。
    同理，由于 category-games 列表包含了 steam、ea、blizzard、epicgames 和 nintendo 等常见的游戏厂商。已设置类别 geosite:category-games@cn 为直连，即可节省大量服务器流量。

    2. 已添加 Disney+ 走代理。    
