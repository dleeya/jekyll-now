
![此处输入图片的描述][1]

----------
- 文本
 
> * 整理知识，学习笔记
> * 发布日记，杂文，所见所想
> * 撰写发布技术文稿（代码支持）
> * 撰写发布学术论文（LaTeX 公式支持）

----------
- 链接
 
> **Github**：[https://github.com/dleeya/dleeya.github.io][2]

------
- 粗体/斜体

> **粗体** 或者 *斜体* 

----------
- 列表
  
>- [ ] 唐朝
- [x] 汉朝

----------
- 质能守恒公式[^LaTeX]

> $E=mc^2$

----------
- 高亮一段代码[^code]

```python
@requires_authorization
class SomeClass:
    pass

if __name__ == '__main__':
    # A comment
    print 'hello world'
```

----------
- 流程图

```flow
st=>start: Start
op=>operation: Your Operation
cond=>condition: Yes or No?
e=>end

st->op->cond
cond(yes)->e
cond(no)->op
```

----------
- 序列图

```seq
Alice->Bob: Hello Bob, how are you?
Note right of Bob: Bob thinks
Bob-->Alice: I am good thanks!
```

----------
- 甘特图]

```gantt
    title 项目开发流程
    section 项目确定
        需求分析       :a1, 2016-06-22, 3d
        可行性报告     :after a1, 5d
        概念验证       : 5d
    section 项目实施
        概要设计      :2016-07-05  , 5d
        详细设计      :2016-07-08, 10d
        编码          :2016-07-15, 10d
        测试          :2016-07-22, 5d
    section 发布验收
        发布: 2d
        验收: 3d
```

----------
- 绘制表格

| 项目        | 价格   |  数量  |
| --------   | -----:  | :----:  |
| 计算机     | \$1600 |   5     |
| 手机        |   \$12   |   12   |
| 管线        |    \$1    |  234  |

----------
- 更详细语法说明

>想要查看更详细的语法说明，可以参考我们准备的 [Cmd Markdown 简明语法手册][3]，进阶用户可以参考 [Cmd Markdown 高阶语法手册][4] 了解更多高级功能。

---
- 图标

> <i class="icon-share"></i> 发布：将当前的文稿生成固定链接，在网络上发布，分享
<i class="icon-file"></i> 新建：开始撰写一篇新的文稿
<i class="icon-trash"></i> 删除：删除当前的文稿
<i class="icon-cloud"></i> 导出：将当前的文稿转化为 Markdown 文本或者 Html 格式，并导出到本地
<i class="icon-reorder"></i> 列表：所有新增和过往的文稿都可以在这里查看、操作
<i class="icon-pencil"></i> 模式：切换 普通/Vim/Emacs 编辑模式
<i class="icon-list"></i> 目录：快速导航当前文稿的目录结构以跳转到感兴趣的段落
<i class="icon-chevron-sign-left"></i> 视图：互换左边编辑区和右边预览区的位置
<i class="icon-adjust"></i> 主题：内置了黑白两种模式的主题，试试 **黑色主题**，超炫！
<i class="icon-desktop"></i> 阅读：心无旁骛的阅读模式提供超一流的阅读体验
<i class="icon-fullscreen"></i> 全屏：简洁，简洁，再简洁，一个完全沉浸式的写作和阅读环境


  [1]: https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1497533002284&di=780403c0d9d775d055a27254af98cd33&imgtype=0&src=http://i.dimg.cc/db/3b/c9/89/3d/44/9d/30/52/4b/f1/76/76/ba/f2/d6.jpg
  [2]: https://github.com/dleeya/dleeya.github.io
  [3]: https://www.zybuluo.com/mdeditor?url=https://www.zybuluo.com/static/editor/md-help.markdown
  [4]: https://www.zybuluo.com/mdeditor?url=https://www.zybuluo.com/static/editor/md-help.markdown#cmd-markdown-高阶语法手册