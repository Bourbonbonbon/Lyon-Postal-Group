里昂邮政集团网站系统 (Lyon Postal Group)

✨ 主要功能

📁 分类内容管理

· 公告管理 - 发布企业公告和通知
· 业务介绍 - 展示各项邮政业务
· 网点清单 - 显示各服务网点信息
· 资费清单 - 展示服务收费标准
· 邮资清单 - 显示邮资相关信息
· 邮品清单 - 展示邮票和集邮产品
· 戳戳我 - 趣味互动图片区域

🛠️ 系统管理

· LOGO自定义 - 支持上传企业LOGO（75×75像素）
· 背景设置 - 可自定义网站背景图片
· 密码保护 - 管理操作需要密码验证
· 本地存储 - 所有数据保存在浏览器本地
· 响应式设计 - 适配桌面和移动设备

📱 用户友好的操作

· 拖放上传 - 支持拖拽文件上传
· 图片预览 - 上传前可预览图片
· 大图查看 - 点击图片可查看原图
· 批量操作 - 支持一次上传最多5张图片
· 即时编辑 - 支持修改和删除现有内容

🚀 快速开始

方法一：直接使用

1. 下载 index.html 文件
2. 用现代浏览器（Chrome/Firefox/Edge）打开
3. 系统立即可用！

方法二：部署到服务器

1. 克隆仓库到您的服务器

```bash
git clone https://github.com/yourusername/lyon-postal-group.git
```

1. 将文件放置在Web服务器目录
2. 通过浏览器访问对应URL

📁 项目结构

```
lyon-postal-group/
├── index.html                    # 主文件（所有功能集成在此）
├── README.md                     # 项目说明文档
├── screenshot/                   # 屏幕截图目录（可选）
│   ├── desktop-view.png
│   └── mobile-view.png
└── assets/                       # 资源文件目录（可选）
    └── sample-images/            # 示例图片
```

🖥️ 技术栈

· 前端：HTML5, CSS3, JavaScript (ES6+)
· 图标库：Font Awesome 6.4.0
· 字体：Segoe UI, Microsoft YaHei
· 存储：浏览器 localStorage API
· 兼容性：现代浏览器（Chrome 60+, Firefox 55+, Safari 11+, Edge 79+）

🔐 安全说明

⚠️ 重要安全提示：

· 当前版本使用前端密码验证，密码明文存储在代码中
· 适合内部使用或演示项目，不推荐用于生产环境
· 如需更高安全性，建议：
  1. 实现后端API进行身份验证
  2. 使用加密存储敏感数据
  3. 添加会话管理功能

📱 浏览器兼容性

浏览器 版本要求 备注
Chrome 60+ 完全支持
Firefox 55+ 完全支持
Safari 11+ 完全支持
Edge 79+ 完全支持
iOS Safari 11+ 完全支持
Android Chrome 60+ 完全支持

🔄 数据管理

数据存储位置

· 所有内容存储在浏览器 localStorage 中
· 键名格式：lyonPost_[分类名]
· 数据格式：JSON序列化

备份与恢复

由于使用本地存储，建议：

1. 定期截图备份重要内容
2. 可导出localStorage数据：
   ```javascript
   // 在浏览器控制台执行
   console.log(JSON.stringify(localStorage));
   ```

🐛 故障排除

常见问题

1. 图片上传失败
   · 检查文件格式（支持JPG/JPEG/PNG）
   · 检查文件大小（建议小于2MB）
   · 确认浏览器支持File API
2. 数据丢失
   · 清除浏览器缓存会删除所有数据
   · 建议定期备份重要内容
3. 页面显示异常
   · 刷新页面重新加载
   · 检查浏览器控制台错误信息
   · 确保JavaScript已启用

开发调试

```javascript
// 清空所有数据
localStorage.clear();

// 查看特定分类数据
console.log(JSON.parse(localStorage.getItem('lyonPost_announcement')));

// 重置管理密码
// 修改DEFAULT_PASSWORD变量值
```

📈 未来计划

计划功能

· 后端API支持
· 用户账户系统
· 数据导出/导入功能
· 图片压缩优化
· 多语言支持
· 统计分析功能

欢迎贡献

1. Fork本仓库
2. 创建功能分支 (git checkout -b feature/AmazingFeature)
3. 提交更改 (git commit -m 'Add some AmazingFeature')
4. 推送到分支 (git push origin feature/AmazingFeature)
5. 创建Pull Request

📄 许可证

本项目采用 MIT 许可证 - 查看 LICENSE 文件了解详情

🤝 贡献者

感谢所有为本项目做出贡献的人：

<a href="https://github.com/yourusername/lyon-postal-group/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=yourusername/lyon-postal-group" />
</a>📞 支持与联系

如有问题或建议，请：

1. 提交 Issue
2. 发送邮件至：contact@lyonpostal.com
3. 访问官网：www.lyonpostal.com

---

里昂邮政集团 - 连接世界的邮递服务
© 2023 里昂邮政集团 版权所有
