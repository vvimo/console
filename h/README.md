# mui_web

> A Vue.js project

## 项目目录结构
``` bash
├─ src
│  ├─ api             // 接口
│  │  └─ .js
│  ├─ assets          // 资源
│  ├─ views           // 界面
│  ├─ components      // vmui-组件
│  │  ├─ button
│  │  │  └─ .js
│  │  └─ tabs
│  ├─ layouts         // 布局
│  │  └─ .vue
│  ├─ libs            // 第三方
│  │  └─ .js
│  ├─ router          // 路由
│  │  ├─ projects
│  │  │  └─ .js
│  │  └─ .js
│  ├─ styl            // vmui-样式
│  │  ├─ logic
│  │  ├─ vmui
│  │  │  ├─ component
│  │  │  └─ helper
│  │  ├─ widget
│  │  └─ .styl
│  ├─ vita            // 个人简历
│  │  ├─ Lyj
│  │  │  ├─ styl
│  │  │  ├─ .vue
│  │  │  └─ assets
│  │  └─ Can
│  └─ projects        // 案例
│     ├─ vimo
│     │  ├─ styl
│     │  ├─ pages
│     │  └─ assets
│     └─ vmui
└─ atatic             // 静态文件
```

## vmui样式目录
``` bash
vmui样式目录
└─styl            // 实际进行开发的样式目录
   ├─logic        // 业务逻辑代码
   ├─vmui         // 总样式文件
   │  ├─component // 基础组件
   │  └─helper    // 助手方法
   ├─widget       // 业务公共组件
   └─var.styl     // 变量
```

## Build Setup
``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
