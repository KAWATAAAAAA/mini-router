# 0.1.5(2022-09-21)
## Features
next方法中支持传递 title，而不是固定的从配置的router 里边取

# 0.1.4(2022-03-07)

## BugFix
修复调用next时，from从dialog-view获取组件name，这是不正确的，应该从dialog.component.name 上获取


# 0.1.0
## Features

- has: () => {}
- next: (options:ComponentMeta ) => {}
- back: () => {}
- find: (name:string) => {}
- registerReplacePoint: (renderComponentRef: VueComponentRef) => {}
- setComponentMap: (val: ComponentMap) => {}
- getRouterRecords: () => RouterRecords

### BugFix



