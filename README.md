# 征地拆迁系统

一个用于管理征地拆迁相关业务的系统，提供完整的业务流程管理、数据统计分析和GIS信息展示功能。

## 项目功能

### 核心模块
- **项目管理**：项目信息管理、标段划分、授权管理
- **房屋管理**：房屋台账、协议管理、补偿标准
- **土地管理**：土地台账、附着物管理
- **审核管理**：审核流程配置、审核台账
- **数据分析**：统计分析、项目统计、拆迁统计、分组统计
- **GIS功能**：GIS数据上传、GIS台账、GIS发布
- **系统管理**：用户角色管理

### 技术特点
- 响应式设计，支持移动端和桌面端
- 模块化架构，便于维护和扩展
- 统一的UI设计规范
- 完整的表单验证和交互反馈
- 支持数据导入导出

## 目录结构

```
├── components/           # 通用组件
│   ├── sidebar.css       # 侧边栏样式
│   ├── sidebar.html      # 侧边栏HTML
│   └── sidebar.js        # 侧边栏脚本
├── agreement-ledger.html # 协议台账
├── attachment-ledger.html # 附着物台账
├── audit-ledger.html     # 审核台账
├── compensation-standard.html # 补偿标准
├── dashboard.html        # 仪表盘
├── data-upload.html      # 数据上传
├── demolition-stats.html # 拆迁统计
├── form-template.html    # 表单模板
├── gis-data-upload.html  # GIS数据上传
├── gis-ledger.html       # GIS台账
├── gis-publish.html      # GIS发布
├── group-stats.html      # 分组统计
├── house-ledger.html     # 房屋台账
├── land-ledger.html      # 土地台账
├── login.html            # 登录页面
├── process-config.html   # 流程配置
├── project-authorization.html # 项目授权
├── project-stats.html    # 项目统计
├── settlement-ledger.html # 结算台账
├── statistics-analysis.html # 统计分析
├── styles.css            # 全局样式
├── template.html         # 页面模板
└── user-role.html        # 用户角色管理
```

## 快速开始

1. 克隆本仓库
2. 在浏览器中打开任意HTML文件即可查看页面效果
3. 建议使用本地服务器运行，例如：
   ```
   python -m http.server 8000
   ```

## 开发说明

- 页面使用HTML、CSS和JavaScript开发
- 样式统一使用CSS定义
- 交互逻辑使用原生JavaScript实现
- 组件化设计，侧边栏等通用组件可复用

## License

MIT