
CherryPy - A Minimalist Python Web Framework
============================================

.. toctree::
   :hidden:

   intro.rst
   install.rst
   tutorials.rst
   basics.rst
   advanced.rst
   config.rst
   extend.rst
   deploy.rst
   support.rst
   contribute.rst
   development.rst
   glossary.rst
   history.rst
   pkg/modules.rst

`CherryPy <http://www.cherrypy.org>`_ 是基于python的，面向对象的web框架.

CherryPy允许开发人员构建Web应用程序，就像构建任何其他面向对象的Python程序一样。这导致在更短的时间内开发更小的源代码。

CherryPy 有超过十年的历史了，事实证明他是快速和可靠的。许多网站使用它来开发产品，囊括最简单的和最复杂的。

一个 CherryPy 程序通常看上去像这样子:　

.. code-block:: python

   import cherrypy

   class HelloWorld(object):
       @cherrypy.expose
       def index(self):
           return "Hello World!"

   cherrypy.quickstart(HelloWorld())


为了充分利用CherryPy, 你应当先阅读 :ref:`tutorials <tutorials>`, 这将使你了解到框架最常见的各个方面。
一旦完成了，你可能想进一步学习 :ref:`basic <basics>` 和 :ref:`advanced <advanced>` 章节，这将演示如何实现某些操作。
最后，你会想仔细越多配置和 :ref:`extend <extend>` 部分，以深入讨论框架提供的强大功能。

最重要的是，享受您的应用程序！
