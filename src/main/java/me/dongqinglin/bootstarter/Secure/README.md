# 概览
```
bean 类型
config 配置
controller 控制器层
converter 类型转化器
entity 实体类
filter 过滤器层，切面编程
repository 仓库层
service 业务层

```

java 中 状态转化是一个伪命题。不同与javascript， java 中状态的转化，经常伴随着类型的转化。
这是由Object的根继承体系所决定的。
对比javascript的弱类型体系，java的强类型在状态转化时，常常伴随着类型的转化，这样就至少具有三个要件：
- 原始状态的类型
- 目标状态的类型
- 转化器
其中，javascript因弱类型，而不必定义目标状态的类型，React+Redux体系充分利用了这一点，构建了状态这一类的核型概念。
然而在强类型语言中，这一概念的实现方式，转变为converter，或者更为古老的util，在强类型语言中，也只有util更加符合弱类型语言发展出的特殊概念。

