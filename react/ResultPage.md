- 开始日期：2024-05-27
- 目标主要版本：(nutui-react 3.x / nutui-react-taro 3.x)
- 参考问题Issues：

# 概括

以页面的形式向用户反馈操作结果。

# 基本示例

代码示例基本和 NutUI-React 网站给出的一致。

# 动机

制定统一的规范，提高组件的使用体验，适配V13设计。

# 详细设计

ResultPage:

| 属性 | 描述 | 类型 | 默认值 |
| --- | --- | --- | --- | --- |
| title | 标题 | ReactNode | - |
| description | 描述，最长两行 | ReactNode | - |
| status | 状态类型 | 'success' \| 'error' \| 'warning' \| 'info' \| 'waiting' | 'info' |
| icon | 自定义 `icon` | ReactNode | - |
| primaryButtonText | 主要操作按钮的文字，默认不显示按钮 | ReactNode | - |
| secondaryButtonText  | 次要操作按钮的文字，默认不显示按钮 | ReactNode | - |
| onPrimaryButtonClick | 点击主要操作按钮后的事件 | () => void | - |
| onSecondaryButtonClick | 点击次要操作按钮后的事件 | () => void | - |

＃ 备择方案

# 采用策略

# 未解决的问题
