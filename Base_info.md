<div id="table-of-contents">
<h2>Table of Contents</h2>
<div id="text-table-of-contents">
<ul>
<li><a href="#sec-1">1. Taskjuggler基本概念</a></li>
<li><a href="#sec-2">2. TJP文件结构</a>
<ul>
<li><a href="#sec-2-1">2.1. 宏变量</a></li>
<li><a href="#sec-2-2">2.2. 标签</a></li>
<li><a href="#sec-2-3">2.3. 账户</a></li>
<li><a href="#sec-2-4">2.4. 资源借用</a></li>
<li><a href="#sec-2-5">2.5. 假期设置</a></li>
<li><a href="#sec-2-6">2.6. 资源池配置</a></li>
<li><a href="#sec-2-7">2.7. 任务列表</a></li>
<li><a href="#sec-2-8">2.8. 项目成本报告</a></li>
<li><a href="#sec-2-9">2.9. 项目资源报告</a></li>
<li><a href="#sec-2-10">2.10. 项目任务报告</a></li>
<li><a href="#sec-2-11">2.11. 文本报告</a></li>
<li><a href="#sec-2-12">2.12. 项目导出</a></li>
</ul>
</li>
</ul>
</div>
</div>


# Taskjuggler基本概念<a id="sec-1" name="sec-1"></a>

Taskjuggler使用一个或多个文本文件来描述一个项目，当一个项目被拆分为多个文件时，最主要的文件名称的后缀必须为 **.tjp** ，而这个主要文件内，可以引入其它多个文件，被引入的文件必须采用 **.tji** 后缀。在主要项目文件中，可以采用如 \*include "inner.tji"\* 的方式引入一个或多个文件。
目前最新的3.5版本中，只能采用命令行的方式使用，因此需要我们选择一个自己习惯使用的编辑器来编写项目即可，然后通过简单的命令来编译完成的项目文件，最终可以生成其它的格式以查看相应的项目报告。
说到编译，实际我们在完成项目文件后，即完成一个 **.tjp** 和其它多个 **.tji** 文件后，可以在当前目录下，打开 **cmd** 或终端，执行一下编译命令。比如我们的项目文件名称叫 **main.tjp** ,因此编译命令则为：

    tj3 main.tjp

以上编译命令，会让taskjuggler来自动对多个文件进行合并计算，Taskjuggler会自动安排所有任务的特殊条件，遇到错误后会提示编译失败的原因，并最终在编译通过后，成功输出文件，如HTML格式的项目报告。文件会最终输出在 **tjp** 所在的相同目录下。

# TJP文件结构<a id="sec-2" name="sec-2"></a>

## 宏变量<a id="sec-2-1" name="sec-2-1"></a>

## 标签<a id="sec-2-2" name="sec-2-2"></a>

## 账户<a id="sec-2-3" name="sec-2-3"></a>

## 资源借用<a id="sec-2-4" name="sec-2-4"></a>

## 假期设置<a id="sec-2-5" name="sec-2-5"></a>

## 资源池配置<a id="sec-2-6" name="sec-2-6"></a>

## 任务列表<a id="sec-2-7" name="sec-2-7"></a>

## 项目成本报告<a id="sec-2-8" name="sec-2-8"></a>

## 项目资源报告<a id="sec-2-9" name="sec-2-9"></a>

## 项目任务报告<a id="sec-2-10" name="sec-2-10"></a>

## 文本报告<a id="sec-2-11" name="sec-2-11"></a>

## 项目导出<a id="sec-2-12" name="sec-2-12"></a>
