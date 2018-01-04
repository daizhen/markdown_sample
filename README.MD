# 1. 标题
---
# Header1
## Header2
### Header3
#### Header4
##### Header5
###### Header6

Header1
==

Header2
--

---

# 2. 引用

>This is a block quote
>END
>> 嵌套引用
>> 嵌套引用

---
# 3. 列表
## 无序列表
* sdf
* sdfsdf
+ 123
+ 123123
- dsfsd 
- dsfsdf

## 有序列表（数字无关）
1. dsfds
1. dsfsdf
4. sdftggg

---

# 4. 代码区（空一行，缩进4个空格）
下面是一个代码区

	 OdbcCommand cmd = conn.CreateCommand();
     cmd.CommandText = sql;
     OdbcDataAdapter adapter = new OdbcDataAdapter(cmd);
     adapter.Fill(set);

下面是三个``` 定义的代码区
```
 OdbcCommand cmd = conn.CreateCommand();
 cmd.CommandText = sql;
 OdbcDataAdapter adapter = new OdbcDataAdapter(cmd);
 adapter.Fill(set);
```
# 5. 分割钱

* * *

***

*****

- - -

---------------------------------------

# 6. 链接 

##  行内式
This is [an example](http://example.com/ "Title") inline link.

[This link](http://example.net/) has no title attribute.

##  参考式
This is [an example] [id] reference-style link.

[id]: http://example.com/  "Optional Title Here" 


# 7. 图片

This is ![an example](http://a5.mzstatic.com/us/r30/Purple4/v4/b2/14/82/b21482fe-6e98-4b18-e40f-14e7d0bb44da/AppIcon.512x512-75.png "Title") inline link.

![This link](http://a5.mzstatic.com/us/r30/Purple4/v4/b2/14/82/b21482fe-6e98-4b18-e40f-14e7d0bb44da/AppIcon.512x512-75.png) has no title attribute.

##  参考式
This is ![an example] [id] reference-style link.

[id]: http://a5.mzstatic.com/us/r30/Purple4/v4/b2/14/82/b21482fe-6e98-4b18-e40f-14e7d0bb44da/AppIcon.512x512-75.png  "Optional Title Here" 

# 8. 代码
`OdbcCommand cmd = conn.CreateCommand();`

