#JEESNS-CORE
免费版不再开源jeesns-core代码，只有授权后才提供全部的代码

##使用说明
将jeesns-core-1.4.jar放到硬盘中，如：D:\jeesns-core-1.4.jar

在命令行中输入以下命令

`mvn install:install-file -Dfile=D:\jeesns-core-1.4.jar -DgroupId=com.lxinet -DartifactId=jeesns-core -Dversion=1.4 -Dpackaging=jar`

执行成功后，jeesns-core-1.4.jar会自动添加到本地maven仓库中。