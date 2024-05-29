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
| actions | 可用于处理操作的一组数据 | `Array` | `[]` |

样式变量

组件提供了下列 CSS 变量，可用于自定义样式，使用方法请参考 [ConfigProvider 组件](#/zh-CN/component/configprovider)。

| 名称 | 说明 | 默认值 |
| --- | --- | --- |
| \--nutui-resultpage-width | 内容区域宽度 | `247px` |
| \--nutui-resultpage-icon-size | icon的宽高 | `48px` |
| \--nutui-resultpage-icon-margin-bottom | icon的margin-bottom值 | `16px` |
| \--resultpage-title-margin-bottom | 标题的margin-top值 | `9px` |
| \--nutui-resultpage-title-font-size | 标题的字体大小 | `$font-size-xl` |
| \---nutui-resultpage-title-color | 标题的文字颜色 | `$color-title` |
| \--nutui-resultpage-description-font-size | 描述的字体大小 | `$font-size-base` |
| \--nutui-resultpage-description-color | 描述的文字颜色 | `$color-text` |
| \--nutui-resultpage-description-line-height | 描述的行高 | `20px` |
| \--nutui-resultpage-actions-margin-topt | 操作区域的margin-top值 | `21px` |

# 备择方案

# 采用策略

# 未解决的问题
