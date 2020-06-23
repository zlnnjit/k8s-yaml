# k8s-yaml
目前支持的k8s资源创建：
+ redis单机版（NodePort:32701）
+ redis主从版（一主三从、NodePort:32702-32703）
+ redis哨兵版(一主三从三哨兵、NodePort:32704-32705)

待支持：
+ redis集群版