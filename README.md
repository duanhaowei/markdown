# learning markdown
编辑的时候，可以先到[作业部落](https://www.zybuluo.com/mdeditor)写，有预览功能，非常强大。<br>
还有强大的[语法手册](https://www.zybuluo.com/mdeditor?url=https://www.zybuluo.com/static/editor/md-help.markdown)

> # 列表
+ item1
+ item2
+ item3
+ item4
+ item5


- [ ] 这个列表功能已经算很强大了
- [ ] 这个列表功能已经算很强大了
- [x] 这个列表功能已经算很强大了
- [x] 这个列表功能已经算很强大了
- [x] 这个列表功能已经算很强大了


> # 文字换行
文本内容，文章里都说换行需要连敲两个回车。
看看不敲的话会怎么样。
好像也没啥问题啊。。。。

预览没问题，上传真的有问题

> # 文字格式

**粗体**    `按键如Alt+F4`   *斜体*     ~~删除线~~    注脚[^footnote]

> # 代码

``` java
@Configuration
@EnableAutoConfiguration
@EnableCircuitBreaker
@EnableGlobalMethodSecurity(securedEnabled = true, prePostEnabled = true)
@SpringBootApplication
@EnableScheduling
public class Application {

	public static void main(String[] args) {
		SpringApplication.run(Application.class, args);
	}

}
```

> #目录结构
`[TOC]`

> #图标
<i class="icon-renren"></i>  详情见[ font-awesome ](http://fortawesome.github.io/Font-Awesome/3.2.1/icons/)

