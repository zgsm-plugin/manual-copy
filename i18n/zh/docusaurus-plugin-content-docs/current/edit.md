---
sidebar_position: 3
---

# 编辑此页

### 简单样式
### 折叠卡
<details>
  <summary>折叠卡片</summary>

  1.  首先，请确保你已经安装了 Docker。
  2.  拉取我们的官方镜像：
      ```bash
      docker pull my-awesome-app
      ```
  3.  运行容器：
      ```bash
      docker run -p 8080:80 my-awesome-app
      ```
  现在，应用应该在 `http://localhost:8080` 上运行了。

</details>


### 选项卡


import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

<Tabs>
  <TabItem value="zgsm" label="zgsm" default>
    这是一个选项卡
  </TabItem>
  <TabItem value="shenma" label="shenma">
    这是选项卡
  </TabItem>
</Tabs>


### 代码块, 高亮显示
```js
function HighlightSomeText(highlight) {
  if (highlight) {
    // highlight-next-line
    return '这行被高亮了！';
  }

  return '这里不会';
}

function HighlightMoreText(highlight) {
  // highlight-start
  if (highlight) {
    return '这块被高亮了！';
  }
  // highlight-end
  return '这里不会';
}
```


### 引用说明
> 引用1 
> 内容