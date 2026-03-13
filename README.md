# 接金币 🪙 - 手机游戏

一个简单有趣的休闲手机游戏，控制碗接住下落的金币！

## 游戏玩法

- **目标**：滑动屏幕控制底部的碗，接住下落的金币
- **得分**：普通金币 +1 分，红色金币 +10 分
- **难度**：随着分数增加，金币下落速度会越来越快

## 运行方式

### 方式一：直接在浏览器运行（推荐先测试）

```bash
# 安装依赖
cd /home/admin/.openclaw/workspace/game-project
npm install

# 启动本地服务器
npx serve www

# 然后访问显示的 localhost 地址
```

### 方式二：打包成 APK（需要 Android SDK）

如果你想在本地构建 APK，需要：

1. **安装 Java JDK 17+**
2. **安装 Android SDK**
3. **配置环境变量 ANDROID_HOME**

然后运行：

```bash
cd /home/admin/.openclaw/workspace/game-project
npm install
npx cap add android
npm run build:android
```

APK 将生成在：`android/app/build/outputs/apk/debug/app-debug.apk`

## 项目结构

```
coin-catch-game/
├── www/
│   └── index.html    # 游戏主文件（可直接在浏览器打开）
├── apk/
│   └── README.txt    # APK 构建说明
├── capacitor.config.json
├── package.json
└── README.md
```

## 快速测试

直接在浏览器中打开 `www/index.html` 即可测试游戏！

## 游戏预览

游戏特性：
- ✅ 触摸/鼠标控制
- ✅ 金币收集计分
- ✅ 难度递增
- ✅ 最高分记录
- ✅ 精美的视觉效果

---

**享受游戏！** 🎮
