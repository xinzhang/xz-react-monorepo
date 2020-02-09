## tutorial for mono repo with react components

Following [tutorial](https://medium.com/hy-vee-engineering/creating-a-monorepo-with-lerna-yarn-workspaces-cf163908965d)

Add dependency need for Babel 7 \
```
yarn add --dev -W @babel/cli @babel/core @babel/preset-react @babel/preset-env babel-core@7.0.0-bridge.0 babel-loader babel-plugin-styled-components webpack
```

Babel note \ 
--root-mode upward for searching node_modules located i the root

Add react and styled component
yarn add --dev -W react react-dom styled-components
