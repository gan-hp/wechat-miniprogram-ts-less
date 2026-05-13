# 标准组件示例

## poster-card.ts
Component<{ title: string }>({
  data: { count: 0 },
  methods: {
    add() {
      this.setData({ count: this.data.count + 1 })
    }
  }
})

## poster-card.wxml
<view class="card">
  <text>{{title}}</text>
  <text>{{count}}</text>
</view>

## poster-card.less
.card { padding: 32rpx; }
