---
title: api
date: 2020/05/29
---

This is api.

:::: code-group 

::: code-group-item 指定首页

```vue
# another-home-path.md
---
title: 指定首页
home: true
---
```



::: 

::: code-group-item 指定首页路径

```vue
// .vuepress/config.ts

import { defineUserConfig } from 'vuepress'
import { recoTheme } from 'vuepress-theme-reco'

export default defineUserConfig({
  theme: recoTheme({
    home: '/another-home-path'
  })
})
```



::: 

::::