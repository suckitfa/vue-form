v-model指令会忽略所有表单元素的value, checked, selected, 属性的初始值，而总是将Vue实例的数据当做数据来源。
- trim 过滤空格
- .lazy 
- .number 将输入数据转为数字类型 (parseFloat)

### 复选框
单个复选框：选中的为true, 为选中的false
多个复选框: 选中的value放入数组中
```js
<input type="checkbox" v-model=""
    true-value="yes"
    false-value="no">
```
