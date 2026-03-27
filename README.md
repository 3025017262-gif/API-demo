# API 测试 Demo

## 项目简介
基于 Postman 的 API 自动化测试示例，验证 GitHub 用户信息接口。

## 测试内容
- **接口地址**：`GET https://api.github.com/users/octocat`
- **断言1**：响应状态码为 200
- **断言2**：返回的 `login` 字段等于 `"octocat"`

## 如何运行
1. 安装 [Postman](https://www.postman.com/downloads/)
2. 下载本仓库中的 `API测试Demo.json` 文件
3. 打开 Postman，点击左上角 **Import** → **Upload Files**，选择该文件导入
4. 在 Collections 中找到 `API测试Demo`，展开后点击请求
5. 点击 **Send** 运行测试
6. 点击 **Test Results** 查看断言结果（应为全部 PASS）

## 测试结果
- 测试用例数：2
- 通过率：100%

## 作者
李阳
