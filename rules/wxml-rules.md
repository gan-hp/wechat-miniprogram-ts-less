# WXML 规范（强约束）

✅ 允许
- {{ a ? b : c }}
- {{ a + 1 }}
- {{ 'hello' + name }}

❌ 禁止
- {{ a?.b }}
- {{ a ?? b }}
- {{ fn() }}
- {{ a++ }}

✅ 列表渲染
<view wx:for="{{list}}" wx:key="id">
