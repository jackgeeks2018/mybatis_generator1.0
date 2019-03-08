#mybait generator 带中文注释
生成带中文注释的类需将com.text.Mycommit 打包成jar并安装到本地仓库

安装jar到本地仓库命令C:\Users\h5848\Desktop\mybatis_generator\classes\artifacts\my_commit
mvn install:install-file -Dfile=C:\Users\h5848\Desktop\mybatis_generator\classes\artifacts\my_commit\my-commit.jar -DgroupId=com.generator -DartifactId=mycommit -Dversion=0.0.1-SNAPSHOT -Dpackaging=jar

