---
order: 0
title:
  zh-CN: 基本
  en-US: Basic Usage
---

## zh-CN

最简单的用法。

## en-US

The simplest use.

```jsx
import { Breadcrumb } from 'antd';

ReactDOM.render(
  <Breadcrumb>
    <Breadcrumb.Item>首页</Breadcrumb.Item>
    <Breadcrumb.Item>
      <a href="">进销存管理</a>
    </Breadcrumb.Item>
    <Breadcrumb.Item>
      <a href="">系统设置</a>
    </Breadcrumb.Item>
    <Breadcrumb.Item>用户信息</Breadcrumb.Item>
  </Breadcrumb>,
  mountNode,
);
```
