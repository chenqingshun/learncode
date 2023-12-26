## 伪类选择器
### :hover
```html
.shun p:hover {
color: blue;
font-weight: 10;
}
```
表示鼠标悬停在shun这个class的p标签内时,字体变成蓝色  
-  :active: 用于指定元素被激活时（例如被点击并按住鼠标），应用的样式。
-  :focus: 用于指定元素获得焦点时（例如输入框被选中），应用的样式。
-  :visited: 用于选择用户已经访问过的链接的样式。
- :first-child, :last-child, :nth-child(): 用于选择特定位置的子元素，并对其应用样式。
- :nth-of-type(), :last-of-type, :first-of-type: 类似于 :nth-child()，但是只匹配特定类型的元素。
- :not(): 用于选择不匹配指定选择器的元素。
- :enabled, :disabled: 用于选择表单元素的启用或禁用状态，并对其应用样式。  
这些伪类选择器可以结合使用，帮助开发者根据不同的状态或条件选择特定的元素，并为其应用样式。