# css命名规范

## 基础
1. 使用类似bem来进行命名而不是嵌套class来实现定位的问题
2. 中划线作为名字的连接符号，只具备连接功能，且所有的命名都应当用中划线来连接。
3. 双下划线代表id，是当前block的唯一元素
4. 单下划线代表类，在当前block中可以有多个
5. block是唯一命名的。
### 例子

```css
.login-panel_input
.login-panel__submit

.main__swiper
.main_swiper-item
```