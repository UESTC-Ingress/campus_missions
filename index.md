## 欢迎来到电子科技大学 Ingress任务索引

在这里你可以查找泛成电地区的任务，也可以提交自己的任务或者对他人的任务进行修改，正式操作之前，请参考[任务创建者手册（待定）](https://missions.nia.ac.cn/Creators/)，以免出现不可预料的偏差。

以下是任务索引：

### 跨校区级别任务
图片(示例) | 名称 | 大小 | 性质 | 预计时间 | 申请状态
{% for post in site.categories.all %}
x | [{{post.title}}]({{ post.url }}) | {{post.size}} | {{post.feature}} | {{post.estimate}} | {{post.status}}
{% endfor %}

### 清水河分区任务
图片(示例) | 名称 | 大小 | 性质 | 预计时间 | 申请状态
{% for post in site.categories.qsh %}
x | [{{post.title}}]({{ post.url }}) | {{post.size}} | {{post.feature}} | {{post.estimate}} | {{post.status}}
{% endfor %}

### 沙河分区任务
图片(示例) | 名称 | 大小 | 性质 | 预计时间 | 申请状态
{% for post in site.categories.sh %}
x | [{{post.title}}]({{ post.url }}) | {{post.size}} | {{post.feature}} | {{post.estimate}} | {{post.status}}
{% endfor %}

### 泛成电任务
图片(示例) | 名称 | 大小 | 性质 | 预计时间 | 申请状态
{% for post in site.categories.fan %}
x | [{{post.title}}]({{ post.url }}) | {{post.size}} | {{post.feature}} | {{post.estimate}} | {{post.status}}
{% endfor %}
