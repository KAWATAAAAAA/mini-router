# setup
```shell
npm i mini-router
```
# usage
```typescript
export declare function useMiniRouter(): {
    has: (name: string) => boolean;
    next: (options: ComponentMeta) => void;
    back: (params?: any) => void;
    find: (name: string) => ComponentMapItem | undefined;
    registerReplacePoint: (renderComponentRef: VueComponentRef) => void;
    setComponentMap: (val: ComponentMap) => void;
    getRouterRecords: () => RouterRecords;
};
```
