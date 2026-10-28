# 紫微斗数 - 每日运势

独立的紫微斗数每日运势查询应用

## 功能特性

- ✨ 两个用户（Jian 和老婆）切换查看
- 📅 每日自动更新运势
- 🌟 四维运势分析（事业/财运/感情/健康）
- 💡 每日建议
- 🎨 支持深色模式
- 📱 响应式设计

## 技术栈

- 纯静态 HTML + CSS + JavaScript
- iztro 紫微斗数排盘库
- Cloudflare Pages 部署

## 用户配置

### Jian
- 出生日期：1994-12-08
- 出生时辰：午时（默认，待确认）
- 出生地点：上海

### 老婆
- 出生日期：1995-02-27
- 出生时辰：午时（默认，待确认）
- 出生地点：上海

## 部署方式

### 方式 1：通过 Cloudflare Dashboard 手动部署

1. 登录 [Cloudflare Dashboard](https://dash.cloudflare.com/)
2. 进入 Pages 项目
3. 创建新项目
4. 上传 `index.html` 文件
5. 部署完成

### 方式 2：通过 Wrangler CLI 部署

```bash
cd ziwei-fortune
npm install
npm run deploy
```

### 方式 3：通过 GitHub Pages 部署

1. 在 GitHub 创建新仓库
2. 上传 `index.html`
3. 在仓库设置中启用 GitHub Pages
4. 访问：`https://你的用户名.github.io/仓库名/`

## 访问地址

部署后访问你的 Cloudflare Pages 域名即可使用。

## 注意事项

- 时辰暂时设为午时（11:00-12:59），需要确认准确出生时间后修改
- 运势计算基于紫微斗数原理，结果仅供参考
- 数据完全在前端计算，不涉及后端服务器

## 后续优化

- [ ] 确认准确出生时辰
- [ ] 接入真实的紫微斗数解读库
- [ ] 添加流月流日详细分析
- [ ] 添加完整命盘展示
- [ ] 保存历史运势记录
