#自定义Maven项目骨架仓库  

##使用说明

1.	在工程根目录下(pom.xml文件所在位置)，执行：`mvn archetype:create-from-project`；
2.	在生成的目录：`target\generated-sources\archetype`下执行：`mvn install`，将项目模板安装到本地  
	maven仓库；
3.	新建一个目录执行命令：`mvn archetype:generate -DarchetypeCatalog=local`，会列出本地的项目模板  
	选择相应的模版即可创建新的项目；

##custom-java-template

+	一个普通的maven java工程模板原型；
+	已包含的第三方库：
	-	junit-->4.9；
	-	logback-->1.0.9；
+	原型生成的新工程最终结构如原型本身结构；

##custom-j2ee-template

+	一个普通的maven j2ee工程模板原型；
+	已包含的第三方库；
	-	junit-->4.9；
	-	logback-->1.0.9；
+	原型生成的新工程最终结构如原型本身结构；
