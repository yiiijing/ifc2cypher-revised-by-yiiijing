# ifc2cypher-revised-by-yiiijing
此文件源代码来自https://gist.github.com/ysangkok/8aa7ab1c3207536518f3c3bf5f664880
本代码修改如下：
1、将ifcopenshell文件打开路径修改为本地打开，对于像我这样的菜鸟而言，使用更加友好
2、自动生成本地txt格式文件，有便于lazywebcypher快速使用
3、建立节点标签，对原代码中ifc节点进行分类，知识图谱呈现更直观
4、对节点关系进行简化，只生成need_class中输入的ifc关系节点，降低数据冗余

超级菜鸟ifc2cypher教程
*本代码需要使用者提前获得ifc数据关系，在need_class中输入对应节点名称，期待有一天有人能实现自动读取ifc架构，生成想要的关系，本菜鸟是做不到了hiahia~~
1、导入.ifc文件：f = ifcopenshell.open('C:\\Users\\Administrator\\Desktop\\python\\test2.ifc')
2、填入.txt结果文件存储地址：data=open("C:\\Users\\Administrator\\Desktop\\python\\store3.txt",'w+') 
3、运行！
4、打开neo4j，使用lazywebcypher导入即可！
