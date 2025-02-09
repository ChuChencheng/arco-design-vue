```yaml
meta:
  type: Arco Pro
title: Directory Structure
description: The organizational structure of the project file.
```

*Auto translate by google.*

## Content

```
├── README.md
├── package.json
├── index.html
├── src
│ ├── api # Request interface
│ ├── assets # Static resources
│ └── style # Global style
│ ├── components # General business components
│ ├── config # Global configuration (including echarts theme)
│ ├── directives # Instruction set (if necessary, you can add it yourself)
│ ├── filters # filter (if necessary, you can add it yourself)
│ ├── hooks # global hooks
│ ├── layout # Layout
│ ├── locale # Internationalized language pack
│ ├── mock # Mock data
│ ├── views # Page template
│ ├── store # State management center
│ ├── types # Routing configuration
│ ├── settings.json # Configuration file
│ └── utils # Tool library
│ └── App.vue # View entrance
│ └── main.ts # Entry file
└── tsconfig.json
```

ps: Filter description<https://v3.cn.vuejs.org/guide/migration/filters.html#%E8%BF%81%E7%A7%BB%E7%AD%96%E7%95%A5 >
