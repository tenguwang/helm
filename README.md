# helm
> helm仓库地址：https://tenguwang.github.io/helm/

1. 添加chart仓库

   ```shell
   ➜  helm repo add dljy https://tenguwang.github.io/helm/
   ```

2. 验证是否添加成功

   ```shell
   ➜  helm repo list
   NAME         	URL
   dljy          	https://tenguwang.github.io/helm/
   ```

3. 更新chart程序

   ```shell
   ➜  helm repo update
   ```

1. 安装chart包

   ```shell
   helm upgrade --install dljy dljy/ --create-namespace -n dljy
   ```

   

