# GameVault 项目结构

GameVault/
├── design.md                    # 游戏导航站点产品需求文档
├── index.html                   # 网站主页（英文版）
├── template.html                # 游戏页面模板
├── sitemap.xml                  # 网站地图
├── games/                       # 游戏分类目录
│   ├── shooting/               # 射击游戏目录
│   │   ├── index.html         # 射击游戏分类页面
│   │   ├── [各游戏HTML文件]   # 各个射击游戏页面
│   │   └── README.md
│   ├── fps/                    # FPS游戏目录
│   │   ├── index.html         # FPS游戏分类页面
│   │   ├── krunker.html       # Krunker游戏页面
│   │   ├── bullet-force.html  # Bullet Force游戏页面
│   │   ├── [其他FPS游戏HTML]  # 其他FPS游戏页面
│   │   └── README.md
│   ├── clicker/               # 点击类游戏目录
│   │   ├── index.html         # 点击类游戏分类页面
│   │   ├── [各游戏HTML文件]   # 各个点击类游戏页面
│   │   └── README.md
│   ├── horror/                # 恐怖游戏目录
│   │   ├── index.html         # 恐怖游戏分类页面
│   │   ├── [各游戏HTML文件]   # 各个恐怖游戏页面
│   │   └── README.md
│   ├── 2players/             # 双人游戏目录
│   │   ├── index.html         # 双人游戏分类页面
│   │   ├── [各游戏HTML文件]   # 各个双人游戏页面
│   │   └── README.md
│   ├── action/               # 动作游戏目录
│   │   ├── index.html         # 动作游戏分类页面
│   │   ├── [各游戏HTML文件]   # 各个动作游戏页面
│   │   └── README.md
│   ├── adventure/            # 冒险游戏目录
│   │   ├── index.html         # 冒险游戏分类页面
│   │   ├── ships3d.html       # Ships 3D 游戏页面
│   │   ├── [其他冒险游戏HTML] # 其他冒险游戏页面
│   │   └── README.md
│   ├── casual/               # 休闲游戏目录
│   │   ├── index.html         # 休闲游戏分类页面
│   │   ├── bubble-tower-3d.html # Bubble Tower 3D游戏页面
│   │   ├── happy-wheels.html  # Happy Wheels游戏页面
│   │   ├── [其他休闲游戏HTML] # 其他休闲游戏页面
│   │   └── README.md
│   ├── sports/               # 体育游戏目录
│   │   ├── index.html         # 体育游戏分类页面
│   │   ├── [各游戏HTML文件]   # 各个体育游戏页面
│   │   └── README.md
│   └── driving/              # 驾驶游戏目录
│       ├── index.html         # 驾驶游戏分类页面
│       ├── [各游戏HTML文件]   # 各个驾驶游戏页面
│       └── README.md

## 说明
这个目录结构基于当前代码库中实际存在的文件和目录。主要包含：

- 根目录文件:
  - 站点设计文档和核心HTML文件
  - 自动生成脚本：generate_game_pages.py和generate_category_pages.py
  - 游戏数据：games_info_by_tags.json

- 游戏目录:
  - 10个游戏分类子目录，每个都包含index.html分类页面
  - 每个分类目录包含该类别的所有游戏HTML页面
  - 所有页面已从中文转换为英文，提供更好的国际用户体验