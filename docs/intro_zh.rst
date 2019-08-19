Foreword
--------

Why CherryPy?
#############

CherryPy是可用于Python的最古老的Web框架之一，但许多人并不知道它的存在。其中一个原因是CherryPy不是一个完整的堆栈，内置支持多层架构。它不提供前端实用程序，也不会告诉您如何与存储区通话。相反，CherryPy的考虑是让开发人员做出这些决定。与其他众所周知的框架相比，这是一个对比鲜明的立场。

cherryPy拥有干净的界面，尽力避开您的方式，同时为您提供可靠的脚手架。

CherryPy的典型用例来自具有用户前端的常规Web应用程序
（仅限博客，CMS，门户网站，电子商务）到网络服务。

以下是您想要选择CherryPy的一些原因：

1. 简单

   基于 CherryPy 开发是一个简单的任务。“Hello, world”　只需要几行代码，并不要求开发人员一次性学习整个(尽管非常易于管理)的框架。这个框架非常的Python化; 也就是说，他很好地遵循Python的约定(代码稀疏且干净)。

   与J2EE和Python最流行和最明显的Web框架相比：Django，Zope，Pylons和Turbogears。在所有这些中，学习曲线是巨大的。在这些框架中，“Hello，world”要求程序员设置一个跨越多个文件并键入大量样板代码的大型脚手架。 CherryPy之所以成功，是因为它不包含其他框架的膨胀，允许程序员快速编写Web应用程序，同时仍保持高水平的组织和可伸缩性。

   CherryPy也非常模块化。核心快速而干净，扩展功能易于使用代码或优雅的配置系统编写和插入。主要组件（服务器，引擎，请求，响应等）都是可扩展的（甚至可替换的）并且管理良好。

   简而言之，CherryPy使开发人员能够使用框架，而不是反对或围绕它。

2. 性能

   CherryPy充分利用了Python的所有功能。 Python是一种动态语言，可以快速开发应用程序。 Python还具有广泛的内置API，可简化Web应用程序开发。然而，更广泛的是可用于Python的第三方库。这些包括从对象关系映射器到表单库，自动Python优化器，Windows exe生成器，映像库，电子邮件支持，HTML模板引擎等。ChanperPy应用程序就像常规Python应用程序一样。如果你想使用这些出色的工具，CherryPy不会阻挡你。 

   CherryPy 同样提供 :ref:`tools <tools>` 和 :ref:`plugins <busplugins>`, 这是开发世界级Web应用程序所需的强大扩展点。

3. 稳定 

   在开发真实世界的应用程序时，成熟度非常重要。与许多其他Web框架不同，CherryPy有许多最终的稳定版本。它经过充分的测试，优化并经过验证，可用于实际应用。 API不会突然改变并破坏向后兼容性，因此即使通过当前版本系列中的后续更新，您的应用程序也可以继续工作。 

   CherryPy也是一个“3.0”项目：第一版CherryPy定下基调，第二版使其成功，第三版使其美观。每个版本都基于前一课程的经验教训，为开发人员提供了一个出色的工具。

4. 社区

   CherryPy有一个专门的社区，开发部署的CherryPy应用程序，并愿意并准备在CherryPy邮件列表或Gitter上为您提供帮助。开发人员也经常使用该列表，并经常回答问题并实现最终用户请求的功能。


5. 部署

   与许多其他Python Web框架不同，部署CherryPy应用程序的方法具有成本效益。

   CherryPy开箱即用，包含自己的生产就绪HTTP服务器来托管您的应用程序。 CherryPy还可以部署在任何符合WSGI的网关（用于连接多种类型的Web服务器的技术）上：mod_wsgi，FastCGI，SCGI，IIS，uwsgi，tornado等。反向代理也是一种常见且简单的设置方式。

   此外，CherryPy是纯python并且与Python 2.3兼容。这意味着CherryPy将在Python将运行的所有主要平台上运行（Windows，MacOSX，Linux，BSD等）。

   `webfaction.com <https://www.webfaction.com>`_, 由CherryPy的发明者运营，是一个商业网站主机，提供CherryPy托管包（除了其他几个）。

6. 免费！

   所有CherryPy都是根据开源BSD许可证授权的，这意味着CherryPy可以在商业上用于零成本。

7. 从这往哪儿去?

   查看 :ref:`tutorials <tutorialz>`, 开始享受乐趣吧！

.. _successstories:

成功的故事
###############

您对CherryPy感兴趣，但您希望听到使用它的人的更多信息，或者只是查看运行它的产品或应用程序。

如果您想在此处列出您的CherryPy网站或产品，请通过我们的网站与我们联系 `mailing list <http://groups.google.com/group/cherrypy-users>`_
或者 `Gitter <https://gitter.im/cherrypy/cherrypy>`_.

基于CherryPy运行的网站
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

`Hulu Deejay and Hulu Sod <http://tech.hulu.com/blog/2013/03/13/python-and-hulu>`_ - Hulu 在一些项目里面使用了CherryPy. "这些服务需要非常高的性能.Python，和CherryPy一起。

`gunicorn <http://gunicorn.org>`_, and gevent more than provides for this."

`Netflix <http://techblog.netflix.com/2013/03/python-at-netflix.html>`_ - Netflix uses CherryPy as a building block in their infrastructure: "Restful APIs to
large applications with requests, providing web interfaces with CherryPy and Bottle,
and crunching data with scipy."

`Urbanility <http://urbanility.com>`_ - French website for local neighbourhood assets in Rennes, France.

`MROP Supply <https://www.mropsupply.com>`_ - Webshop for industrial equipment,
developed using CherryPy 3.2.2 utilizing Python 3.2,
with libs: `Jinja2-2.6 <http://jinja.pocoo.org/docs>`_, davispuh-MySQL-for-Python-3-3403794,
pyenchant-1.6.5 (for search spelling).
"I'm coming over from .net development and found Python and CherryPy to
be surprisingly minimalistic.  No unnecessary overhead - build everything you
need without the extra fluff.  I'm a fan!"

`CherryMusic <http://www.fomori.org/cherrymusic>`_ - A music streaming server written in python:
Stream your own music collection to all your devices! CherryMusic is open source.

`YouGov Global <http://www.yougov.com>`_ - International market research firm, conducts
millions of surveys on CherryPy yearly.

`Aculab Cloud <http://cloud.aculab.com>`_ - Voice and fax applications on the cloud.
A simple telephony API for Python, C#, C++, VB, etc...
The website and all front-end and back-end web services are built with CherryPy,
fronted by nginx (just handling the ssh and reverse-proxy), and running on AWS in two regions.

`Learnit Training <http://www.learnit.nl>`_ - Dutch website for an IT, Management and
Communication training company. Built on CherryPy 3.2.0 and Python 2.7.3, with
`oursql <http://pythonhosted.org/oursql>`_ and
`DBUtils <http://www.webwareforpython.org/DBUtils>`_ libraries, amongst others.

`Linstic <http://linstic.com>`_ - Sticky Notes in your browser (with linking).

`Almad's Homepage <http://www.almad.net>`_ - Simple homepage with blog.

`Fight.Watch <http://fight.watch>`_ - Twitch.tv web portal for fighting games.
Built on CherryPy 3.3.0 and Python 2.7.3 with Jinja 2.7.2 and SQLAlchemy 0.9.4.

Products based on CherryPy
^^^^^^^^^^^^^^^^^^^^^^^^^^

`SABnzbd <http://sabnzbd.org>`_ - Open Source Binary Newsreader written in Python.

`Headphones <https://github.com/rembo10/headphones>`_  - Third-party add-on for SABnzbd.

`SickBeard <http://sickbeard.com>`_ - "Sick Beard is a PVR for newsgroup users (with limited torrent support). It watches for new episodes of your favorite shows and when they are posted it downloads them, sorts and renames them, and optionally generates metadata for them."

`TurboGears <http://www.turbogears.org>`_ - The rapid web development megaframework. Turbogears 1.x used Cherrypy. "CherryPy is the underlying application server for TurboGears. It is responsible for taking the requests from the userâ€™s browser, parses them and turns them into calls into the Python code of the web application. Its role is similar to application servers used in other programming languages".

`Indigo <http://www.perceptiveautomation.com/indigo/index.html>`_ - "An intelligent home control
server that integrates home control hardware modules to provide control of your home. Indigo's built-in
Web server and client/server architecture give you control and access to your home remotely from
other Macs, PCs, internet tablets, PDAs, and mobile phones."

`SlikiWiki <http://www.sf.net/projects/slikiwiki>`_ - Wiki built on CherryPy and featuring WikiWords, automatic backlinking, site map generation, full text search, locking for concurrent edits, RSS feed embedding, per page access control lists, and page formatting using PyTextile markup."

`read4me <http://sourceforge.net/projects/read4me>`_ - read4me is a Python feed-reading web service.

`Firebird QA tools <http://www.firebirdsql.org/en/quality-assurance>`_ - Firebird QA tools are based on CherryPy.

`salt-api <https://github.com/saltstack/salt-api>`_ - A REST API for Salt, the infrastructure orchestration tool.

Products inspired by CherryPy
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

`OOWeb <http://ooweb.sourceforge.net/>`_ - "OOWeb is a lightweight, embedded HTTP server for Java applications that maps objects to URL directories, methods to pages and form/querystring arguments as method parameters. OOWeb was originally inspired by CherryPy."
