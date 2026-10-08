## 安装教程：
### 方式 1 — VS Code 命令面板（推荐）：
  - 打开 VS Code
  - `Ctrl+Shift+P` → 输入`Extensions: Install from VSIX...`
  - 选择`.vsix` 文件 → 重启 VS Code
   
### 方式 2 — 命令行：
  `code --install-extension ai-frontend-0.1.0.vsix`

## 配置后端地址：
### 方法 1 — VS Code 设置界面：
  - `Ctrl+,` 打开设置
  - 搜索`backendUrl`
  - 填入后端地址，`http://192.168.1.103:3000`（目前没有使用服务器，后端直接部署在我的电脑）
### 方法 2 — settings.json 直接写：
  - `Ctrl + Shift + P` → 打开命令面板
  - 输入 `Preferences: Open User Settings (JSON)` → 回车并输入：
    ```
    {
    "ai-assistant.backendUrl": "http://192.168.1.100:3000"
    }
    ```
改完重启 VS Code 即可生效。
