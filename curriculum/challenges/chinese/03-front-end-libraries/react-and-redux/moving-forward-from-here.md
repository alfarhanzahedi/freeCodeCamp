---
id: 5a24c314108439a4d403614a
title: 从这里前进
challengeType: 6
forumTopicId: 301434
---

# --description--

恭喜你完成了 React 和 Redux 的所有课程！在继续前进前，还有一点值得我们注意。通常，我们不会在这样的编辑器中编写 React 应用代码。如果你在自己的计算机上使用 npm 和文件系统，这个挑战可让你一瞥 React 应用的语法之貌。除了使用`import`语句（这些语句引入了各挑战中提供的所有依赖关系），其代码看起来类似。“管理包（含 npm）”这一节更详细地介绍了 npm。

最后，写 React 和 Redux 的代码通常需要一些配置，且很快会变得复杂起来。如果你想在自己的机器上尝试写代码，点击链接

[创建 React App](https://github.com/facebookincubator/create-react-app)可获取已配置好的现成代码。

另一种做法是在 CodePen 中启用 Babel 作为 JavaScript 预处理器，将 React 和 ReactDOM 添加为外部 JavaScript 资源，在那里编写应用。

# --instructions--

把`'Now I know React and Redux!'`这一消息输出到控制台。

# --hints--

`Now I know React and Redux!`这一消息应输出到控制台。

```js
(getUserInput) =>
  assert(
    /console\s*\.\s*log\s*\(\s*('|"|`)Now I know React and Redux!\1\s*\)/.test(
      getUserInput('index')
    )
  );
```

# --solutions--

