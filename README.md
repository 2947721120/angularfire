##CN 机器翻译请参照EN原版理解
<article class="markdown-body entry-content" itemprop="text"><h1><a id="user-content-angularfire" class="anchor" href="#angularfire" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="AngularFire" data-dst="angularfire" style="background: transparent;">angularfire</trans></h1>

<p><a href="https://travis-ci.org/firebase/angularfire"><img src="https://camo.githubusercontent.com/b7fe002416ac5042b9209df0c85fb2070808147a/68747470733a2f2f7472617669732d63692e6f72672f66697265626173652f616e67756c6172666972652e7376673f6272616e63683d6d6173746572" alt="Build Status" data-canonical-src="https://travis-ci.org/firebase/angularfire.svg?branch=master" style="max-width:100%;"></a>
<a href="https://coveralls.io/github/firebase/angularfire?branch=master"><img src="https://camo.githubusercontent.com/c11b86ea99db8958003f2e7061199f5e7e857cc8/68747470733a2f2f636f766572616c6c732e696f2f7265706f732f66697265626173652f616e67756c6172666972652f62616467652e7376673f6272616e63683d6d617374657226736572766963653d676974687562" alt="Coverage Status" data-canonical-src="https://coveralls.io/repos/firebase/angularfire/badge.svg?branch=master&amp;service=github" style="max-width:100%;"></a>
<a href="http://badge.fury.io/gh/firebase%2Fangularfire"><img src="https://camo.githubusercontent.com/2ccfaa476c210ec0c01dad745b3183e1e409d406/68747470733a2f2f62616467652e667572792e696f2f67682f6669726562617365253246616e67756c6172666972652e737667" alt="Version" data-canonical-src="https://badge.fury.io/gh/firebase%2Fangularfire.svg" style="max-width:100%;"></a></p>

<p><trans data-src="AngularFire is the officially supported " data-dst="angularfire是官方支持">angularfire是官方支持</trans><a href="http://angularjs.org/"><trans data-src="AngularJS" data-dst="AngularJS"><trans data-src="AngularJS" data-dst="AngularJS">AngularJS</trans></trans></a><trans data-src=" binding for
" data-dst="结合">结合</trans><a href="http://www.firebase.com/?utm_medium=web&amp;utm_source=angularfire"><trans data-src="Firebase" data-dst="火力点">火力点</trans></a><trans data-src=". Firebase is a
backend service that provides data storage, authentication, and static website hosting for your Angular app." data-dst="。火力点是一个
后端服务提供数据存储、验证、静态网站托管你的角的应用。" style="background: transparent;">。火力点是一个
后端服务提供数据存储、验证、静态网站托管你的角的应用。</trans></p>

<p><trans data-src="AngularFire is a complement to the core Firebase client. It provides you with three Angular
services:" data-dst="angularfire是核心客户的补充火力点。它为你提供了三角
服务：" style="background: transparent;">angularfire是核心客户的补充火力点。它为你提供了三角
服务：</trans></p>

<ul>
<li><code><trans data-src="$firebaseObject" data-dst="firebaseobject美元">firebaseobject美元</trans></code><trans data-src=" - synchronized objects" data-dst="同步对象" style="background: transparent;">同步对象</trans></li>
<li><code><trans data-src="$firebaseArray" data-dst="firebasearray美元">firebasearray美元</trans></code><trans data-src=" - synchronized collections" data-dst="同步的集合" style="background: transparent;">同步的集合</trans></li>
<li><code><trans data-src="$firebaseAuth" data-dst="firebaseauth美元">firebaseauth美元</trans></code><trans data-src=" - authentication, user management, routing" data-dst="认证、用户管理、路由" style="background: transparent;">认证、用户管理、路由</trans></li>
</ul>

<h2><a id="user-content-downloading-angularfire" class="anchor" href="#downloading-angularfire" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Downloading AngularFire" data-dst="angularfire下载">angularfire下载</trans></h2>

<p><trans data-src="In order to use AngularFire in your project, you need to include the following files in your HTML:" data-dst="为了在你的项目中使用angularfire，你需要包括在您的HTML文件：" style="background: transparent;">为了在你的项目中使用angularfire，你需要包括在您的HTML文件：</trans></p>

<div class="highlight highlight-text-html-basic"><pre><span class="pl-c"><trans data-src="<!-- AngularJS -->" data-dst="<！angularjs——>——" style="background: transparent;">&lt;！angularjs——&gt;——</trans></span>
&lt;<span class="pl-ent"><trans data-src="script" data-dst="脚本">脚本</trans></span> <span class="pl-e"><trans data-src="src" data-dst="SRC">SRC</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="https://ajax.googleapis.com/ajax/libs/angularjs/1.5.0/angular.min.js" data-dst="http：/ / / / / angularjs ajax.googleapis.com AJAX库/ / angular.min.js 1.5.0">http：/ / / / / angularjs ajax.googleapis.com AJAX库/ / angular.min.js 1.5.0</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span>&gt;&lt;/<span class="pl-ent"><trans data-src="script" data-dst="脚本">脚本</trans></span>&gt;

<span class="pl-c"><trans data-src="<!-- Firebase -->" data-dst="<！firebase————>">&lt;！firebase————&gt;</trans></span>
&lt;<span class="pl-ent"><trans data-src="script" data-dst="脚本">脚本</trans></span> <span class="pl-e"><trans data-src="src" data-dst="SRC">SRC</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="https://cdn.firebase.com/js/client/2.4.0/firebase.js" data-dst="cdn.firebase.com https：／／／／／／firebase.js 2.4.0客户端js">cdn.firebase.com https：／／／／／／firebase.js 2.4.0客户端js</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span>&gt;&lt;/<span class="pl-ent"><trans data-src="script" data-dst="脚本">脚本</trans></span>&gt;

<span class="pl-c"><trans data-src="<!-- AngularFire -->" data-dst="<！angularfire————>">&lt;！angularfire————&gt;</trans></span>
&lt;<span class="pl-ent"><trans data-src="script" data-dst="脚本">脚本</trans></span> <span class="pl-e"><trans data-src="src" data-dst="SRC">SRC</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="https://cdn.firebase.com/libs/angularfire/1.2.0/angularfire.min.js" data-dst="http：/ / / / / angularfire LIBS cdn.firebase.com / angularfire.min.js 1.2.0">http：/ / / / / angularfire LIBS cdn.firebase.com / angularfire.min.js 1.2.0</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span>&gt;&lt;/<span class="pl-ent"><trans data-src="script" data-dst="脚本">脚本</trans></span>&gt;</pre></div>

<p><trans data-src="Use the URL above to download both the minified and non-minified versions of AngularFire from the
Firebase CDN. You can also download them from the
" data-dst="使用上述URL下载的压缩和非压缩版本的angularfire从
 Firebase CDN。你也可以从下载">使用上述URL下载的压缩和非压缩版本的angularfire从
 Firebase CDN。你也可以从下载</trans><a href="https://github.com/firebase/angularfire/releases"><trans data-src="releases page of this GitHub repository" data-dst="这个GitHub库发布的页面">这个GitHub库发布的页面</trans></a><trans data-src=".
" data-dst="。">。</trans><a href="https://www.firebase.com/docs/web/quickstart.html?utm_medium=web&amp;utm_source=angularfire"><trans data-src="Firebase" data-dst="火力点">火力点</trans></a><trans data-src=" and
" data-dst="和">和</trans><a href="https://angularjs.org/"><trans data-src="Angular" data-dst="角">角</trans></a><trans data-src=" libraries can be downloaded directly from their respective websites." data-dst="图书馆可以直接下载从各自的网站。">图书馆可以直接下载从各自的网站。</trans></p>

<p><trans data-src="You can also install AngularFire via npm and Bower and its dependencies will be downloaded
automatically:" data-dst="你也可以通过安装angularfire NPM和凉亭及其依赖项将自动下载
：">你也可以通过安装angularfire NPM和凉亭及其依赖项将自动下载
：</trans></p>

<div class="highlight highlight-source-shell"><pre><trans data-src="$ npm install angularfire --save" data-dst="新安装angularfire --拯救美元">新安装angularfire --拯救美元</trans></pre></div>

<div class="highlight highlight-source-shell"><pre><trans data-src="$ bower install angularfire --save" data-dst="鲍尔安装angularfire --拯救美元">鲍尔安装angularfire --拯救美元</trans></pre></div>

<p><trans data-src="Once you've included AngularFire and its dependencies into your project, you will have access to
the " data-dst="一旦你有angularfire及其依赖关系到你的项目，你将有机会获得
的">一旦你有angularfire及其依赖关系到你的项目，你将有机会获得
的</trans><code><trans data-src="$firebase" data-dst="firebase美元">firebase美元</trans></code><trans data-src=" service." data-dst="服务">服务</trans></p>

<h2><a id="user-content-getting-started-with-firebase" class="anchor" href="#getting-started-with-firebase" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Getting Started with Firebase" data-dst="开始发">开始发</trans></h2>

<p><trans data-src="AngularFire uses Firebase for data storage and authentication. You can " data-dst="angularfire用于数据存储和认证发。你可以">angularfire用于数据存储和认证发。你可以</trans><a href="https://www.firebase.com/signup/?utm_medium=web&amp;utm_source=angularfire"><trans data-src="sign up here for a free
account" data-dst="在这里注册一个免费的
帐户">在这里注册一个免费的
帐户</trans></a><trans data-src="." data-dst="。">。</trans></p>

<h2><a id="user-content-documentation" class="anchor" href="#documentation" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Documentation" data-dst="文档">文档</trans></h2>

<p><trans data-src="The Firebase docs have a " data-dst="医生有一个火力">医生有一个火力</trans><a href="https://www.firebase.com/docs/web/bindings/angular/quickstart.html?utm_medium=web&amp;utm_source=angularfire"><trans data-src="quickstart" data-dst="快速入门">快速入门</trans></a><trans data-src=",
" data-dst="，">，</trans><a href="https://www.firebase.com/docs/web/bindings/angular/guide?utm_medium=web&amp;utm_source=angularfire"><trans data-src="guide" data-dst="指南">指南</trans></a><trans data-src=",
and " data-dst="，
">，
</trans><a href="https://www.firebase.com/docs/web/bindings/angular/api.html?utm_medium=web&amp;utm_source=angularfire"><trans data-src="full API reference" data-dst="完整的API参考">完整的API参考</trans></a><trans data-src="
for AngularFire." data-dst="对于angularfire。">对于angularfire。</trans></p>

<p><trans data-src="We also have a " data-dst="我们也有一个">我们也有一个</trans><a href="https://www.firebase.com/tutorial/#tutorial/angular/0?utm_medium=web&amp;utm_source=angularfire"><trans data-src="tutorial" data-dst="教程">教程</trans></a><trans data-src="
to help you get started with AngularFire." data-dst="为了帮助你开始angularfire。">为了帮助你开始angularfire。</trans></p>

<p><trans data-src="Join our " data-dst="加入我们">加入我们</trans><a href="https://groups.google.com/forum/#!forum/firebase-angular"><trans data-src="Firebase + Angular Google Group" data-dst="发角谷歌集团">发角谷歌集团</trans></a><trans data-src="
to ask questions, provide feedback, and share apps you've built with AngularFire." data-dst="问问题，提供反馈和共享应用程序你建立了与angularfire。">问问题，提供反馈和共享应用程序你建立了与angularfire。</trans></p>

<h2><a id="user-content-contributing" class="anchor" href="#contributing" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Contributing" data-dst="贡献">贡献</trans></h2>

<p><trans data-src="If you'd like to contribute to AngularFire, you'll need to run the following commands to get your
environment set up:" data-dst="如果你想为angularfire，你需要运行下面的命令来让你的
环境设置：">如果你想为angularfire，你需要运行下面的命令来让你的
环境设置：</trans></p>

<div class="highlight highlight-source-shell"><pre><trans data-src="$ git clone https://github.com/firebase/angularfire.git
$ " data-dst="$ git clone https：／／angularfire.git 
美元/ firebase github.com">$ git clone https：／／angularfire.git 
美元/ firebase github.com</trans><span class="pl-c1"><trans data-src="cd" data-dst="CD">CD</trans></span><trans data-src=" angularfire            " data-dst="angularfire">angularfire</trans><span class="pl-c"><trans data-src="# go to the angularfire directory" data-dst="#去angularfire目录">#去angularfire目录</trans></span><trans data-src="
$ npm install -g grunt-cli  " data-dst="NPM安装- G咕噜CLI美元">NPM安装- G咕噜CLI美元</trans><span class="pl-c"><trans data-src="# globally install grunt task runner" data-dst="繁重的任务#全球安装转轮">繁重的任务#全球安装转轮</trans></span><trans data-src="
$ npm install               " data-dst="$ NPM安装">$ NPM安装</trans><span class="pl-c"><trans data-src="# install local npm build / test dependencies" data-dst="#安装本地NPM制造/测试的依赖关系">#安装本地NPM制造/测试的依赖关系</trans></span><trans data-src="
$ grunt install             " data-dst="为繁重的安装">为繁重的安装</trans><span class="pl-c"><trans data-src="# install Selenium server for end-to-end tests" data-dst="#安装服务器端对端测试硒">#安装服务器端对端测试硒</trans></span><trans data-src="
$ grunt watch               " data-dst="咕噜看美元">咕噜看美元</trans><span class="pl-c"><trans data-src="# watch for source file changes" data-dst="#看源文件的变化">#看源文件的变化</trans></span></pre></div>

<p><code><trans data-src="grunt watch" data-dst="咕噜看">咕噜看</trans></code><trans data-src=" will watch for changes in the " data-dst="注意观察变化的">注意观察变化的</trans><code><trans data-src="/src/" data-dst="Src的/ /">Src的/ /</trans></code><trans data-src=" directory and lint, concatenate, and minify the
source files when a change occurs. The output files - " data-dst="目录和皮棉，连接，和缩小
源文件发生变化时。输出文件—">目录和皮棉，连接，和缩小
源文件发生变化时。输出文件—</trans><code><trans data-src="angularfire.js" data-dst="angularfire.js"><trans data-src="angularfire.js" data-dst="angularfire.js">angularfire.js</trans></trans></code><trans data-src=" and " data-dst="和">和</trans><code><trans data-src="angularfire.min.js" data-dst="angularfire.min.js"><trans data-src="angularfire.min.js" data-dst="angularfire.min.js">angularfire.min.js</trans></trans></code><trans data-src=" -
are written to the " data-dst="- 
写入">- 
写入</trans><code><trans data-src="/dist/" data-dst="/距离/">/距离/</trans></code><trans data-src=" directory. " data-dst="目录">目录</trans><code><trans data-src="grunt watch" data-dst="咕噜看">咕噜看</trans></code><trans data-src=" will also re-run the unit tests every time you
update any source files." data-dst="也将重新运行单元测试，每一次你
更新任何源文件。">也将重新运行单元测试，每一次你
更新任何源文件。</trans></p>

<p><trans data-src="You can run the entire test suite via the command line using " data-dst="你可以运行整个测试套件通过命令行使用">你可以运行整个测试套件通过命令行使用</trans><code><trans data-src="grunt test" data-dst="繁重的测试">繁重的测试</trans></code><trans data-src=". To only run the unit
tests, run " data-dst="。只有运行单元
测试运行">。只有运行单元
测试运行</trans><code><trans data-src="grunt test:unit" data-dst="咕噜：单元测试">咕噜：单元测试</trans></code><trans data-src=". To only run the end-to-end " data-dst="。只运行端到端">。只运行端到端</trans><a href="https://github.com/angular/protractor/"><trans data-src="Protractor" data-dst="量角器">量角器</trans></a><trans data-src="
tests, run " data-dst="测试运行">测试运行</trans><code><trans data-src="grunt test:e2e" data-dst="咕噜：端到端的测试">咕噜：端到端的测试</trans></code><trans data-src="." data-dst="。">。</trans></p>
</article>

##EN
# AngularFire

[![Build Status](https://travis-ci.org/firebase/angularfire.svg?branch=master)](https://travis-ci.org/firebase/angularfire)
[![Coverage Status](https://coveralls.io/repos/firebase/angularfire/badge.svg?branch=master&service=github)](https://coveralls.io/github/firebase/angularfire?branch=master)
[![Version](https://badge.fury.io/gh/firebase%2Fangularfire.svg)](http://badge.fury.io/gh/firebase%2Fangularfire)

AngularFire is the officially supported [AngularJS](http://angularjs.org/) binding for
[Firebase](http://www.firebase.com/?utm_medium=web&utm_source=angularfire). Firebase is a
backend service that provides data storage, authentication, and static website hosting for your Angular app.

AngularFire is a complement to the core Firebase client. It provides you with three Angular
services:
  * `$firebaseObject` - synchronized objects
  * `$firebaseArray` - synchronized collections
  * `$firebaseAuth` - authentication, user management, routing


## Downloading AngularFire

In order to use AngularFire in your project, you need to include the following files in your HTML:

```html
<!-- AngularJS -->
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.5.0/angular.min.js"></script>

<!-- Firebase -->
<script src="https://cdn.firebase.com/js/client/2.4.0/firebase.js"></script>

<!-- AngularFire -->
<script src="https://cdn.firebase.com/libs/angularfire/1.2.0/angularfire.min.js"></script>
```

Use the URL above to download both the minified and non-minified versions of AngularFire from the
Firebase CDN. You can also download them from the
[releases page of this GitHub repository](https://github.com/firebase/angularfire/releases).
[Firebase](https://www.firebase.com/docs/web/quickstart.html?utm_medium=web&utm_source=angularfire) and
[Angular](https://angularjs.org/) libraries can be downloaded directly from their respective websites.

You can also install AngularFire via npm and Bower and its dependencies will be downloaded
automatically:

```bash
$ npm install angularfire --save
```

```bash
$ bower install angularfire --save
```

Once you've included AngularFire and its dependencies into your project, you will have access to
the `$firebase` service.


## Getting Started with Firebase

AngularFire uses Firebase for data storage and authentication. You can [sign up here for a free
account](https://www.firebase.com/signup/?utm_medium=web&utm_source=angularfire).


## Documentation

The Firebase docs have a [quickstart](https://www.firebase.com/docs/web/bindings/angular/quickstart.html?utm_medium=web&utm_source=angularfire),
[guide](https://www.firebase.com/docs/web/bindings/angular/guide?utm_medium=web&utm_source=angularfire),
and [full API reference](https://www.firebase.com/docs/web/bindings/angular/api.html?utm_medium=web&utm_source=angularfire)
for AngularFire.

We also have a [tutorial](https://www.firebase.com/tutorial/#tutorial/angular/0?utm_medium=web&utm_source=angularfire)
to help you get started with AngularFire.

Join our [Firebase + Angular Google Group](https://groups.google.com/forum/#!forum/firebase-angular)
to ask questions, provide feedback, and share apps you've built with AngularFire.


## Contributing

If you'd like to contribute to AngularFire, you'll need to run the following commands to get your
environment set up:

```bash
$ git clone https://github.com/firebase/angularfire.git
$ cd angularfire            # go to the angularfire directory
$ npm install -g grunt-cli  # globally install grunt task runner
$ npm install               # install local npm build / test dependencies
$ grunt install             # install Selenium server for end-to-end tests
$ grunt watch               # watch for source file changes
```

`grunt watch` will watch for changes in the `/src/` directory and lint, concatenate, and minify the
source files when a change occurs. The output files - `angularfire.js` and `angularfire.min.js` -
are written to the `/dist/` directory. `grunt watch` will also re-run the unit tests every time you
update any source files.

You can run the entire test suite via the command line using `grunt test`. To only run the unit
tests, run `grunt test:unit`. To only run the end-to-end [Protractor](https://github.com/angular/protractor/)
tests, run `grunt test:e2e`.
