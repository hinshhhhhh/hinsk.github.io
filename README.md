# 魔法图书

## 项目整体架构

- 1.基于Java，使用**MVP**架构搭建，View和Presenter分离
- 2.网络框架封装基于：**Rx + Retrofit2 + okHttp3**
- 3.数据库采用**Realm**(支持Rx)
- 4.图片加载采用 **Glide**
- 5.使用**Hawk**替代SharedPreference(加密，存复杂数据类型)
- 6.日志采集工具：**Timber** 和 **Hugo**(跟踪方法执行时间)
- 7.内存泄露检测：**LeakCanary**
- 8.控件注解：**ButterKnife**
- 9.**自定义RxBus**代替事务总线
