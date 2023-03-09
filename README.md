# 常用的 C4-Model

- Person: 人员
- System: 系统， 包括 DB,Application, WebPage 等
- System_ext: 外部系统
- System_Boundary:系统边界，在这个边界中的都是系统的组成部分，里面一般是 Container 级别的组件
- Container:容器，不是 Docker 之类的容器，简单点可以直接理解为 System 的组成部分，比如 DB、Application 等
- ContainerDb:DB
- Container_Boundary:容器边界，在这个边界范围内的都是容器的组成部分，里面一般都是 Component 级别的数据
- Component:组件，比如一个 Controller，一个 Service 逻辑处理类，一个 Domain 等
- Rel:连接线
