# apt-get安装jdk8

- 安装python-software-properties

```shell
sudo apt-get install python-software-properties
sudo apt-get install software-properties-common
```

- 添加ppa

```shell
sudo add-apt-repository ppa:webupd8team/java
```

- 然后更新系统

```shell
sudo apt-get update
```

- 最后开始安装

```shell
sudo apt-get install oracle-java8-installer
java -version
```

--------

java版本切换

```shell
sudo update-java-alternatives -s java-8-oracle
```
