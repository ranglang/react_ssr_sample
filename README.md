# React + Typescript + SSR + Code Splitting

code splitting with @loadable/components

createdon : 2020. 04. 24

## 작업일 기준 Version

- react-dom@16.13.1
- react@16.13.1
- typescript@3.8.3
- styled-components@5.1.0
- @types/react-dom@16.9.6
- tslint@6.1.1
- @types/react@16.9.34
- webpack-dev-server@3.10.3
- babel-loader@8.1.0
- html-webpack-plugin@4.2.0
- webpack-cli@3.3.11
- ts-loader@7.0.1
- webpack@4.43.0
- express@4.17.1
- webpack-node-externals@1.7.2
- @types/webpack-node-externals@1.7.1
- @types/webpack-hot-middleware@2.25.2
- @types/webpack-dev-middleware@3.7.0
- webpack-dev-middleware@3.7.2
- @types/express@4.17.6
- webpack-hot-middleware@2.25.0
- @types/webpack-env@1.15.2
- @babel/core@7.9.0
- @babel/plugin-transform-runtime@7.9.0

## Setting Guide

위 가이드는 React + Typescript + SSR + Code Splitting으로 환경 구성 하는 방법 입니다.

#### 폴더 구조

```bash
root
  ├─.github
  │  └─workflows
  ├─dist
  ├─src
  │  ├─components
  │  ├─pages
  │  ├─App.tsx
  │  ├─index.tsx
  │  └─server.tsx
  └─...config files
```

#### 설정

```bash
npm install react react-dom typescript styled-components
npm install @types/react @types/react-dom tslint --save-dev

npm install webpack webpack-cli webpack-dev-server html-webpack-plugin babel-loader ts-loader --save-dev

npm install react-router-dom react-helmet
npm install @types/react-router-dom @types/react-helmet --save-dev

npm install express
npm install cors webpack-dev-middleware webpack-hot-middleware webpack-node-externals @types/cors @types/express @types/webpack-dev-middleware @types/webpack-hot-middleware @types/webpack-env --save-dev

# code splitting (with loadable/components)
npm install @loadable/component
npm install @types/loadable__component --save-dev
```
