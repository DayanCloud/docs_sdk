.. _header-n0:

初窥SDK
========

.. _header-n2:

概览
----

.. code:: 

   我们开放一个简单的Python SDK来更方便地使用我们的三维重建服务；
   这个官方渲染SDK由 大雁云 的 RD团队维护开发；
   这个渲染SDK在 python3.6 下测试通过;

.. _header-n5:

为什么要使用渲染SDK
-------------------

.. code:: 

   1. 自动化。SDK将使用云渲染服务的流程（分析场景、上传资产、渲染、下载）全部自动化。
   2. 开源。用户可自定义开发或提交开发建议
   3. 跨平台，支持windows和linux(其中dayan_sync只支持Windows和centos7及以上)
   4. 安全性高。使用动态签名算法认证（HmacSHA256 + Base64 + UTC时间戳限时认证 + 随机数防止重放攻击），更安全
   5. 提供多种使用方式。支持本地分析和不本地分析
   6. 独立性好。将API与业务逻辑独立开来，易扩展
   7. 有详细文档

.. _header-n8:

支持的软件
----------

-  ContextCapture

.. _header-n19:

准备工作
--------

1. 您需要一个 `DayanCloud <https://www.dayancloud.com/>`__ 账号

2. 您还需要在 `DayanCloud
   开发者中心 <https://www.dayancloud.com/>`__
   申请使用渲染SDK，并获取AccessID和AccessKey

 注意：大雁云官网暂未开放开发者中心，如有需要请联系大雁云研发

.. _header-n26:

安装相应模块
------------

详细的安装方法参考 `安装指南 <installation_guide.html>`_

.. _header-n29:

开始使用
--------
    参考 `SDK入门教程 <SDK_tutorial.html>`_

.. _header-n33:

参数设置请参考
--------------

-  `详细参数配置 <para_configration.html>`_

.. _header-n37:

更多
----

-  `常见全流程样例 <demo/index.html>`_
