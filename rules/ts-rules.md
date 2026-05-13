# TypeScript 规范

✅ 允许
- interface / type
- async / await
- Promise
- 枚举

❌ 禁止
- ?.
- ??
- any（无注释）
- window / document
- Node.js API

✅ 示例
interface User {
  id: number
  nickname: string
}
