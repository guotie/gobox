# 流程

## 配置文件
server : {
	port: ,
	listen: 0.0.0.0,
	hosts_allow: [],
	hosts_deny: []
}

client: {
	servers: {
		"main": {
			
		},
		"backup": {
			
		}
	},
	
	dirs: [ {
		path: "",
		exclude: [],
		options: {
			
		}
	}
	]
}

## 客户端流程
 
1 连接服务器端

2 查看本地索引，是否所有path都已经索引


### 同步流程

同步时，抽象出一个client端和一个server端，两端是对等的。

