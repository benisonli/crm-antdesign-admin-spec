# crm-antdesign-admin-spec｜演示场景设计

## 目标
为发布页准备“这个 skill 到底怎么用、能产出什么”的演示场景。

---

## Demo Scenario 1
### 标题
Turn a vague request into the right page type

### 输入
> Design an AI customer insights page for a CRM system.

### Skill 应该先做什么
- 判断页面类型：**AI analytics page**
- 而不是普通 statistics page

### 应输出的关键内容
- 页面目标
- 页面信息架构
- KPI + insight cards + trends + detail table + action recommendations
- Ant Design 组件映射
- 不该做成营销风 AI 页

### 发布页可展示要点
**Before:** vague dashboard request  
**After:** clear AI analytics page structure

---

## Demo Scenario 2
### 标题
Stop turning list pages into dashboards

### 输入
> Design a customer management page with filters and actions.

### Skill 应该先做什么
- 判断页面类型：**List page**

### 应输出的关键内容
- 筛选区
- 操作区
- 表格区
- 分页区
- 列表页约束与禁止项

### 发布页可展示要点
**Before:** dashboard-like layout tendency  
**After:** proper admin list-page structure

---

## Demo Scenario 3
### 标题
Separate config pages from analytics pages

### 输入
> Design an AI analysis settings page.

### Skill 应该先做什么
- 判断页面类型：**Configuration / tool page**

### 应输出的关键内容
- 左侧功能导航
- 右侧配置表单
- Upload / InputNumber / Select / Tooltip / Config table
- Ant Design 配置页实现思路

### 发布页可展示要点
**Before:** dashboard misuse  
**After:** proper config/tool page skeleton

---

## 推荐发布页展示结构
每个 demo 块建议展示：
1. 用户原始请求
2. Skill 的页面类型判断
3. 正确骨架图
4. 关键约束说明
5. 可继续喂给 UI generation 的 Prompt 结果
