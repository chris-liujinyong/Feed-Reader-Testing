# 项目简介

这个项目是一个基于 Web 的 RSS 反馈阅读 应用程序。该项目使用了 [Jasmine](http://jasmine.github.io) ，一共包含7个测试套件。

# 如何运用该项目

1. 查看 Jasmine spec 文件 **./jasmine/spec/feedreader.js** 然后翻阅阅读 [Jasmine 文档](http://jasmine.github.io)。
2. 用户可以编辑 **./js/app.js** 里面的 `allFeeds` 变量使给出的测试通不过，然后观察Jasmine展示应用的错误信息。
3. 该项目在 **./jasmine/spec/feedreader.js** 里面写了一个 `"RSS Feeds"` 的测试用例
4. 该项目在 **./jasmine/spec/feedreader.js** 里面编写了一个测试保证 allFeeds 变量被定义了而且不是空的。
5. 该项目在 **./jasmine/spec/feedreader.js** 里面编写了一个测试遍历 allFeeds 对象里面的所有的源来保证有链接字段而且链接不是空的。
6. 该项目在 **./jasmine/spec/feedreader.js** 里面编写了一个测试遍历 allFeeds对象里面的所有的源来保证有名字字段而且不是空的。
7. 该项目在 **./jasmine/spec/feedreader.js** 里面写了一个 `"The menu"` 的测试用例。
8. 该项目在 **./jasmine/spec/feedreader.js** 里面编写了一个测试用例保证菜单元素默认是隐藏的。
9. 该项目在 **./jasmine/spec/feedreader.js** 里面编写了一个测试用例保证当菜单图标被点击的时候菜单会切换可见状态。
10. 该项目在 **./jasmine/spec/feedreader.js** 里面写了一个 `"Initial Entries"` 的测试用例。
11. 该项目在 **./jasmine/spec/feedreader.js** 里面编写了一个测试保证 `loadFeed` 函数被调用而且工作正常。
12. 该项目在 **./jasmine/spec/feedreader.js** 里面写了一个 `"New Feed Selection"` 的测试用例。
13. 该项目在 **./jasmine/spec/feedreader.js** 里面编写了一个测试保证当用 `loadFeed` 函数加载一个新源的时候内容会改变。
14. 每个测试都是分别独立的。
