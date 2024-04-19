# Accounting
用vue语法实现的简单记账清单的功能
## 1. 基本渲染
**created** 请求数据**(封装渲染方法)** -> 将数据更新给data -> 数据动态渲染
## 2. 添加功能
收集表单数据**v-model** -> 点击发送,添加请求-> **重新渲染(封装渲染方法)**
## 3. 删除功能
点击按钮**传递id** -> 根据id发送删除请求 -> **重新渲染(封装渲染方法)**
## 4. 饼图渲染
**mounted** 初始化 echarts实例 -> 渲染函数中**setOption** 动态更新饼图(**map**)
## 5. 示意图
[![Accounting](https://img.17carat.cn/2024/04/github/Accounting.png "Accounting")](https://img.17carat.cn/2024/04/github/Accounting.png "Accounting")
