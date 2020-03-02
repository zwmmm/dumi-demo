```jsx
/**
 * title: 标题内容JSX
 * desc: 我是简介，我可以用 `Markdown` 来编写
 * background: '#f6f7f9'
 */

import React from "react";
import { Button } from "antd";
import "antd/dist/antd.css";

export default () => <Button type="primary">antd 的按钮</Button>;
```

```jsx | inline
import React from "react";
import { Button } from "antd";
import "antd/dist/antd.css";

export default () => <Button type="primary">antd 的按钮 inline</Button>;
```
