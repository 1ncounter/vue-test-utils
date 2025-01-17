# 介绍

Vue Test Utils 是 Vue.js 官方的单元测试实用工具库。

<div class="vueschool"><a href="https://vueschool.io/courses/learn-how-to-test-vuejs-components?friend=vuejs" target="_blank" rel="sponsored noopener" title="Learn how to use Vue Test Utils to test Vue.js Components with Vue School">在 Vue School 学习如何测试 Vue.js 组件</a></div>

- [安装](installation/)
  - [选择一个测试运行器](installation/choosing-a-test-runner.md)
  - [用 Jest 测试单文件组件](installation/testing-single-file-components-with-jest.md)
  - [用 Mocha 和 webpack 测试单文件组件](installation/testing-single-file-components-with-mocha-webpack.md)
  - [用 Karma 测试单文件组件](installation/testing-single-file-components-with-karma.md)
  - [无需构建在 Node.js 中测试](installation/usage-without-a-build-step-node.md)
- [教程](guides/)
  - [起步](guides/getting-started.md)
  - [常用技巧](guides/common-tips.md)
  - [鼠标、键盘以及其它 DOM 事件](guides/dom-events.md)
  - [测试异步行为](guides/testing-async-components.md)
  - [配合 TypeScript 使用](guides/using-with-typescript.md)
  - [配合 Vue Router 使用](guides/using-with-vue-router.md)
  - [配合 Vuex 使用](guides/using-with-vuex.md)
  - [有用的测试库](guides/useful-libraries-for-testing.md)
- [API](api/)
  - [mount](api/mount.md)
  - [shallowMount](api/shallowMount.md)
  - [render](api/render.md)
  - [renderToString](api/renderToString.md)
  - [挂载选项](api/options.md)
    - [context](api/options.md#context)
    - [slots](api/options.md#slots)
    - [scopedSlots](api/options.md#scopedslots)
    - [stubs](api/options.md#stubs)
    - [mocks](api/options.md#mocks)
    - [localVue](api/options.md#localvue)
    - [attachToDocument](api/options.md#attachtodocument)
    - [attrs](api/options.md#attrs)
    - [propsData](api/options.md#propsdata)
    - [listeners](api/options.md#listeners)
    - [parentComponent](api/options.md#parentComponent)
    - [provide](api/options.md#provide)
    - [其它选项](api/options.md#other-options)
  - [Wrapper](api/wrapper/)
    - [attributes](api/wrapper/attributes.md)
    - [classes](api/wrapper/classes.md)
    - [contains](api/wrapper/contains.md)
    - [emitted](api/wrapper/emitted.md)
    - [emittedByOrder](api/wrapper/emittedByOrder.md)
    - [exists](api/wrapper/exists.md)
    - [destroy](api/wrapper/destroy.md)
    - [find](api/wrapper/find.md)
    - [findAll](api/wrapper/findAll.md)
    - [get](api/wrapper/get.md)
    - [html](api/wrapper/html.md)
    - [is](api/wrapper/is.md)
    - [isEmpty](api/wrapper/isEmpty.md)
    - [isVueInstance](api/wrapper/isVueInstance.md)
    - [name](api/wrapper/name.md)
    - [props](api/wrapper/props.md)
    - [setChecked](api/wrapper/setChecked.md)
    - [setData](api/wrapper/setData.md)
    - [setMethods](api/wrapper/setMethods.md)
    - [setProps](api/wrapper/setProps.md)
    - [setSelected](api/wrapper/setSelected.md)
    - [setValue](api/wrapper/setValue.md)
    - [text](api/wrapper/text.md)
    - [trigger](api/wrapper/trigger.md)
    - [isVisible](api/wrapper/isVisible.md)
  - [WrapperArray](api/wrapper-array/)
    - [at](api/wrapper-array/at.md)
    - [contains](api/wrapper-array/contains.md)
    - [exists](api/wrapper/exists.md)
    - [destroy](api/wrapper-array/destroy.md)
    - [filter](api/wrapper-array/filter.md)
    - [is](api/wrapper-array/is.md)
    - [isEmpty](api/wrapper-array/isEmpty.md)
    - [isVueInstance](api/wrapper-array/isVueInstance.md)
    - [setChecked](api/wrapper-array/setChecked.md)
    - [setData](api/wrapper-array/setData.md)
    - [setMethods](api/wrapper-array/setMethods.md)
    - [setProps](api/wrapper-array/setProps.md)
    - [setValue](api/wrapper-array/setValue.md)
    - [trigger](api/wrapper-array/trigger.md)
    - [isVisible](api/wrapper-array/isVisible.md)
  - [组件](api/components/)
    - [RouterLinkStub](api/components/RouterLinkStub.md)
  - [选择器](api/selectors.md)
  - [createWrapper](api/createWrapper.md)
  - [createLocalVue](api/createLocalVue.md)
  - [配置](api/config.md)
