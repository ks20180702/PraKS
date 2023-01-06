项目的位置和注意事项
======================

婺城预警短信生成 
---------------------

**时间 1-??号**

    1. `婺城短信git地址`_
    2. 本地电脑文件地址: `C:\Users\metgs\JinHua\WuChengRiskService\scripts\ShortPrRiskMonitor`
    3. `婺城短信项目相关公司文档地址`_
    4. 此项目叫应联系人等问题还没确定，07-20时短信生成部分有一个bug，平均面雨量可能为nan。

洞头活动计算推荐天数
------------------------

**时间 21号**

    1. `洞头活动git地址`_
    2. 本地电脑文件地址: `C:\Users\metgs\project\dongtou\dongtousguarantee2021\Script\JudgeSuitDaySaveValue`
    3. 洞头活动项目相关公司文档地址: 无
    4. `洞头活动前端网站`_
    5. `东头活动活动管理网站`_

处理10.135.32.122上的FcstServer出现僵尸进程的问题
-------------------------------------------------

**时间 15号**

    1. `僵尸进程git地址`_
    2. 本地电脑文件地址: `C:\Users\metgs\ks\APython\project\KillDefunctProcess`
    3. 僵尸进程项目相关公司文档地址: 无

数据仓获取mv_station_info资料代码入库 + 小时分钟数据入库
---------------------------------------------------------

**时间 7-14号**

    1. `数据仓站点git地址`_
    2. 本地电脑文件地址: `C:\Users\metgs\base\mapi_script\AwsHourMinuteSyncFromDw`
    3. `数据仓站点项目相关公司文档地址`_
    4. 部署到婺城服务器上，包含小时同步、分钟同步、分钟整点同步整小时3个脚本，由于MCron总会停掉，故布置在计划任务中。
    5. 分钟数据，每分钟同步最近10分钟的数据，手动同步比较快，但是自动跑好像时间很长，可能会导致问题。

增加24小时最大积雪深度变量入库
--------------------------------------------------

**时间 13号**

    1. `增加最大积雪深度git地址`_
    2. 本地电脑文件地址: `C:\Users\metgs\zjobs\dmo_v2`
    3. 增加最大积雪深度项目相关公司文档地址: 无
    4. 此项目改动很小，主要对原有的代码增加一些配置，其中服务器转的好像很麻烦。

天擎下载浙江短临3公里累计降雨nc文件下载
-------------------------------------------------

**时间 12号**

    1. `天擎ncgit地址`_
    2. 本地电脑文件地址: `C:\Users\metgs\JinHua\WuChengRiskService\scripts\PrNcFileLoadFromMusic`
    3. 天擎项目相关公司文档地址: 无
    4. 由于数据仓无法获取到3小时预报数据，故尝试从天擎获取，当天擎中的隔10分钟好像只有最近两小时的数据。

兰溪烟雨指数计算
-------------------------------------------------

**时间 9号**

    1. `兰溪烟雨git地址`_
    2. 本地电脑文件地址: `C:\Users\metgs\ks\APython\project\LanXiMistyRainIndex`
    3. 兰溪烟雨项目相关公司文档地址: 无

ERA5数据同步相关
-------------------------------------------------

**时间 1号**

    1. `ERA5数据git地址`_
    2. 本地电脑文件地址: `C:\Users\metgs\ks\APython\project\LanXiMistyRainIndex`
    3. `ERA5数据项目相关公司文档地址`_
    4. 使用rustDest连接中转，然后才能登上。

.. _婺城短信git地址: http://moon.metgs.com:1107/project/jinhua/WuChengRiskService/tree/mdev/scripts/ShortPrRiskMonitor
.. _婺城短信项目相关公司文档地址: http://moon.metgs.com/docs/_gen_ProjectMeteorology/Met-ZheJiang-JinHua/MG-PRO-WuChengMeteorological.php
.. _洞头活动git地址: http://moon.metgs.com:1107/project/dongtou/dongtousguarantee2021
.. _洞头活动前端网站: https://eleven.metgs.com/dongtou/activity-service/
.. _东头活动活动管理网站: https://eleven.metgs.com/dongtou/metservice/back/#/
.. _僵尸进程git地址: http://moon.metgs.com:1107/project/Universal/MGScripts
.. _数据仓站点git地址: http://moon.metgs.com:1107/base/mapi_script
.. _数据仓站点项目相关公司文档地址: http://moon.metgs.com/docs/_gen_ProjectMeteorology/Met-ZheJiang-JinHua/MG-PRO-WuCheng.php
.. _增加最大积雪深度git地址: https://eleven.metgs.com/dongtou/metservice/back/#/
.. _天擎ncgit地址: http://moon.metgs.com:1107/project/jinhua/WuChengRiskService
.. _兰溪烟雨git地址: http://moon.metgs.com:1107/project/lanxi/travel
.. _ERA5数据git地址: http://moon.metgs.com:1107/project/zjobs/MDataCenter/tree/master/ERA5FileDownLoad
.. _ERA5数据项目相关公司文档地址: http://moon.metgs.com/docs/_gen_ProjectMeteorology/Met-Zhejiang-Province/MG-PRO-ZjPortal-Research.php
