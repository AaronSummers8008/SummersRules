### 思路： 
因为生活在国内,自然绝大多数服务走的是国内的,因此完全不需要手动写那么多国内分流策略.
直接把QuantumultX分流策略中的`Final`配置为`Direct`,  
而对于需要走国外代理的服务器来讲再单独编写分流规则,工作量会小很多.  
`Final`在**分流规则**里面可以找到，单独成一条，能够直接进行配置。

### 目录： 
`ProxyRules.list`主要-代理配置文件  
`Reject.list`主要-广告拦截  
`RejectUseless`确认无效的拦截地址  
`UpdateReference.txt`拦截地址参考资料
测似
