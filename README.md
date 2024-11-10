# FlyIMCore

## 创建私有仓库

```shell
pod spec create FlyIMCore
```

```shell
pod repo add mypods https://github.com/ammmnia/pods.git
```

## 测试

新建一个项目，并添加podfile

```
pod init
```

## 推送

```
pod repo push mypods FlyIMCore.podspec --allow-warnings  
```

```
pod trunk push
```