# helm

> helm仓库地址：https://tenguwang.github.io/helm/

1. 添加chart仓库

   ```shell
   ➜  helm repo add pta https://tenguwang.github.io/helm/
   ```

   

2. 验证是否添加成功

   ```shell
   ➜  helm repo list
   NAME         	URL
   pta          	https://tenguwang.github.io/helm/
   ```

3. 搜索chart包

   ```shell
   ➜  helm search repo pta
   NAME          	CHART VERSION	APP VERSION	DESCRIPTION
   bitnami/moodle	16.1.6       	4.2.1      	Moodle(TM) LMS is an open source online Learnin..
   ```

4. 安装chart包

   ```shell
   helm install pta pta/dljy
   ```

   

