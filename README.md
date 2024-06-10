<!-- lang: java -->
<p align="center">
	<img alt="logo" src="favicon.png">
</p>
<h1 align="center" style="margin: 30px 0 30px; font-weight: bold;">open v1.0.1</h1>
<h4 align="center">基于SpringBoot+Vue前后端分离的轻量级数据开放平台</h4>
<p align="center">
	<a href="https://gitee.com/webusi/open/stargazers"><img src="https://gitee.com/webusi/open/badge/star.svg?theme=dark"></a>
	<a href="https://gitee.com/webusi/open/blob/master/LICENSE"><img src="https://img.shields.io/github/license/mashape/apistatus.svg"></a>
</p>

## 平台简介

数据开放平台 通过整合优质站点的数据能力，为客户或内部用户提供数据统一查询能力。<p/>
主要功能包括：数据源管理、数据接口管理、接口授权、IP白名单、调用日志、充值记录、接口数据。<p/>

* 前端采用Vue、Element UI。
* 后端采用Spring Boot、Spring Security、Redis & Jwt。
* 权限认证使用Jwt，支持多终端认证系统。
* 支持加载动态权限菜单，多方式轻松权限控制。
* 高效率开发，使用代码生成器可以一键生成前后端代码。
* 提供了技术栈（[Vue3](https://v3.cn.vuejs.org) [Element Plus](https://element-plus.org/zh-CN) [Vite](https://cn.vitejs.dev)）版本。
* 特别鸣谢：[element](https://github.com/ElemeFE/element)，[vue-element-admin](https://github.com/PanJiaChen/vue-element-admin)，[eladmin-web](https://github.com/elunez/eladmin-web)。

## 团队产品
https://www.webusi.net

## 更新日志
### 1.0.1 2024-06-10
1.  功能：新增SQL接口，支持根据sql语句生成数据接口
2.  优化：若干Bug

### 1.0.0 2024-05-10
1.  功能：数据源管理、数据接口管理、接口授权、IP白名单
2.  功能：调用日志、充值记录、接口数据
3.  功能：统一查询接口

## 核心功能
1.  数据源管理：配置数据源，支持数据库源、HTTP源
2.  数据接口管理：配置数据源的数据接口
3.  接口授权：授权接口调用权限给客户
4.  IP白名单：限制允许调用的IP
5.  调用日志：记录每一次调用情况
6.  充值记录：记录充值记录
7.  接口数据：保存接口数据
8.  统一查询：面向内外部用户，提供统一查询数据接口

## 基础功能

1.  用户管理：用户是系统操作者，该功能主要完成系统用户配置。
2.  部门管理：配置系统组织机构（公司、部门、小组），树结构展现支持数据权限。
3.  岗位管理：配置系统用户所属担任职务。
4.  菜单管理：配置系统菜单，操作权限，按钮权限标识等。
5.  角色管理：角色菜单权限分配、设置角色按机构进行数据范围权限划分。
6.  字典管理：对系统中经常使用的一些较为固定的数据进行维护。
7.  参数管理：对系统动态配置常用参数。
8.  通知公告：系统通知公告信息发布维护。
9.  操作日志：系统正常操作日志记录和查询；系统异常信息日志记录和查询。
10. 登录日志：系统登录日志记录查询包含登录异常。
11. 在线用户：当前系统中活跃用户状态监控。
12. 定时任务：在线（添加、修改、删除)任务调度包含执行结果日志。
13. 代码生成：前后端代码的生成（java、html、xml、sql）支持CRUD下载 。
14. 系统接口：根据业务代码自动生成相关的api接口文档。
15. 服务监控：监视当前系统CPU、内存、磁盘、堆栈等相关信息。
16. 缓存监控：对系统的缓存信息查询，命令统计等。
17. 连接池监视：监视当前系统数据库连接池状态，可进行分析SQL找出系统性能瓶颈。

## 演示图
<table>
    <tr>
        <td><img src="open/open-1.png"/></td>
        <td><img src="open/open-2.png"/></td>
    </tr>
    <tr>
        <td><img src="open/open-3.png"/></td>
        <td><img src="open/open-4.png"/></td>
    </tr>
    <tr>
        <td><img src="open/open-5.png"/></td>
        <td><img src="open/open-6.png"/></td>
    </tr>
    <tr>
        <td><img src="open/open-7.png"/></td>
    </tr>
</table>


## 知识库交流

QQ： 43530640