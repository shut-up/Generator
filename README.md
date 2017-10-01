# Generator
mybatis逆向工程（实现数据库到Java对象的映射）：
1、
generatorConfig-base.xml
generatorConfig-business.xml
generatorConfig-base.xml
三个配置文件，此只用到generatorConfig.xml，generatorConfig.xml需要根据实际数据库的内容进行修改

2、主程序位于src/GeneratorSqlmap.java中，运行改程序,则在cn.itcast.ssm中生成对应的文件
