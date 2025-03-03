#商品价格追踪器（Price Tracker）

一个基于 **Flask + Web Scraping + SQLite** 的 Web 应用，可以自动跟踪指定商品的价格变化，并在降价时发送通知。

## 功能
爬取 固定商品的价格
记录价格变化，并可视化历史趋势
价格下降时，自动发送邮件通知
支持 API 查询价格（未来扩展）

## 🛠 技术栈
- **Python + Flask**（后端框架）
- **Requests + BeautifulSoup**（网页爬取）
- **SQLite**（数据库存储）
- **Matplotlib**（数据可视化）
- **Flask-Mail**（邮件通知）
- **GitHub Actions**（自动更新数据）

## 安装
