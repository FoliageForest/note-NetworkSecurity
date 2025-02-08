`msfconsole` 启动交互终端  

## msfconsole

`banner`  
`show exploits` : 显示入侵  
`show auxiliary`  
`show post`  
`show evasion`  
`show encoders`  
`help search`  
`search mysql`  
`search cve-2021-44228`  
`search ms17-010`  
`info 5` : 使用 `search` 后，进一步使用 `info` 查看查询结果详细信息  
`use xxxx` : 使用模块  
`back`  
`exit`/`quit`  


### use

`set rhosts 192.168.138.12`  
`show options`  
`run` : 开始利用漏洞进行攻击  
`back` : 退出  

### 一些可用的模块

#### scanner/portscan/tcp

端口扫描

#### auxiliary/scanner/discovery/arp_sweep

`search arp_sweep`  
`use auxiliary/scanner/discovery/arp_sweep`  
