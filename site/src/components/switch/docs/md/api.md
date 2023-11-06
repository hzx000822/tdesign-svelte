[//]: # (:: BASE_DOC ::)

[//]: # (## API)
[[toc]]
### Switch Props

名称 | 类型 | 默认值 | 说明 | 必传
-- | -- | -- | -- | --
customValue | Array | - | 用于自定义开关的值，[打开时的值，关闭时的值]。默认为 [true, false]。示例：[1, 0]、['open', 'close']。JS 类型：`Array<SwitchValue>` | N
disabled | Boolean | undefined | 是否禁用组件。优先级：Switch.disabled > Form.disabled | N
label | Array   | [] | 开关内容，[开启时内容，关闭时内容]。示例：['开', '关'] 。JS 类型：`Array<string>`。[通用类型定义](https://github.com/Tencent/tdesign-vue-next/blob/develop/src/common.ts) | N
labelOpen | Slot | undefined | 开启时内容 | N
labelClose | Slot | undefined | 关闭时内容 | N
loading | Boolean | false | 是否处于加载中状态 | N
size | String | medium | 开关尺寸。可选项：small/medium/large | N
value | String / Number / Boolean | - | 开关值。支持语法糖 `bind:value`。JS 类型：`T` `type SwitchValue = string \| number \| boolean`。[详细类型定义](https://github.com/Tencent/tdesign-vue-next/tree/develop/src/switch/type.ts) | N
defaultValue | String / Number / Boolean | - | 开关值。非受控属性。JS 类型：`T` `type SwitchValue = string \| number \| boolean`。[详细类型定义](https://github.com/Tencent/tdesign-vue-next/tree/develop/src/switch/type.ts) | N
onChange | Function |  | JS 类型：`(value: T, context: { e: MouseEvent }) => void`<br/>数据发生变化时触发 | N

### Switch Events

名称 | 参数 | 描述
-- | -- | --
change | `(value: T, context: { e: MouseEvent })` | 数据发生变化时触发