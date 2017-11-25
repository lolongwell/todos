# vue-todos
基于Vue的todos示例

## 技术栈
Vue + localStorage + hash

## 功能描述(使用说明)
- 添加备忘录(输入标题后回车添加,如果内容为空或只有空格会清空，什么都不添加)
- 删除备忘录(点击标题后面的叉)
- 完成备忘录(点击标题前面的复选框)
- 编辑备忘录(双击标题进入编辑模式)
- 取消编辑备忘录(按ESC或者失去焦点时)
- 完成编辑备忘录(按回车键完成[如果内容为空的时候会自动删除]，此时也会调用到失去焦点事件)
- 一键完成所有备忘录(点击第一行的复选框)
- 过滤任务，显示全部，未完成，已完成的备忘录(点击全部，未完成，已完成按钮)
- 清空已完成备忘录(点击清空已完成)

## Vue相关知识点练习：

- el选项挂载DOM
- 属性
- 计算属性（get,set）
- 属性观察
- 方法
- 指令
