# audio-prototype 文件结构

期末作业由 index.html 主页面、serve.js 本地服务脚本，以及 js/ 目录下 system1-ambience-v2.js、system1-art.js、system2-footstep.js、system3-dashboard.js、system3-engine.js、system4-reverb.js 等核心模块，配合 assets/audio/ 目录下的全部音频素材共同组成，具体搭建模式如下述树状图所示：

```
audio-prototype/
├── index.html                          (28 KB)
├── serve.js                            (1.2 KB)
├── 丈徽杩.bat                           (0.4 KB)
│
├── js/
│   ├── app.js                          (29 KB)
│   ├── file-fetch.js                   (2 KB)
│   ├── system1-ambience-v2.js          (35 KB)
│   ├── system1-art.js                  (54 KB)
│   ├── system2-footstep.js             (9.5 KB)
│   ├── system3-dashboard.js            (16 KB)
│   ├── system3-engine.js              (9 KB)
│   └── system4-reverb.js              (26 KB)
│
└── assets/
    └── audio/
        ├── AMB_2D_EXT_GEN.wav          (17.4 MB)
        ├── OBJ_Campfire_Crack_01.wav   (789 KB)
        ├── OBJ_Campfire_Crack_02.wav   (1.0 MB)
        ├── OBJ_Campfire_Crack_03.wav   (769 KB)
        ├── OBJ_Campfire_Crack_04.wav   (837 KB)
        ├── OBJ_Campfire_Crack_05.wav   (856 KB)
        ├── OBJ_Campfire_Crack_06.wav   (1.3 MB)
        ├── OBJ_Campfire_Crack_07.wav   (1.0 MB)
        ├── OBJ_Campfire_Sizzle_01.wav  (1.0 MB)
        ├── OBJ_Campfire_Sizzle_02.wav  (1.2 MB)
        ├── OBJ_Campfire_Sizzle_03.wav  (1.1 MB)
        ├── OBJ_Campfire_Sizzle_04.wav  (1.4 MB)
        ├── OBJ_Campfire_Sizzle_05.wav  (1.3 MB)
        ├── OBJ_Campfire_Sizzle_06.wav  (1.1 MB)
        ├── OBJ_Campfire_Sizzle_07.wav  (1.0 MB)
        ├── OBJ_cricket_sizzle.mp3       (155 KB)
        ├── OBJ_Thunderstorm.mp3        (2.9 MB)
        ├── OBJ_Wind_BigWind.mp3        (1.2 MB)
        ├── onlyvoice_humantest1.wav    (1.2 MB)
        ├── onlyvoice_humantest2.wav    (3.2 MB)
        ├── onlyvoice_humantest3.wav    (1.7 MB)
        ├── water_deep.wav              (160 KB)
        ├── water_middle.wav            (195 KB)
        ├── water_shallow.wav           (74 KB)
        │
        ├── AMB_Forest/
        │   ├── AMB_Forest_2D_Insect_Group_Night.wav       (17.3 MB)
        │   ├── AMB_Forest_2D_Wind_Gentle.wav              (17.3 MB)
        │   ├── AMB_Forest_3D_Bird_Owl_Hoot_01.wav         (827 KB)
        │   ├── AMB_Forest_3D_Bird_Owl_Hoot_02.wav         (888 KB)
        │   ├── AMB_Forest_3D_Bird_Owl_Hoot_03.wav         (818 KB)
        │   ├── AMB_Forest_3D_Bird_Owl_Hoot_04.wav         (810 KB)
        │   ├── AMB_Forest_3D_Bird_Owl_Hoot_05.wav         (816 KB)
        │   ├── AMB_Forest_3D_Insect_Cricket_02.wav         (70 KB)
        │   ├── AMB_Forest_3D_Insect_Cricket_03.wav         (62 KB)
        │   ├── AMB_Forest_3D_Insect_Cricket_04.wav         (60 KB)
        │   ├── AMB_Forest_3D_Insect_Cricket_05.wav         (64 KB)
        │   ├── AMB_Forest_3D_Insect_Cricket_06.wav         (70 KB)
        │   ├── AMB_Forest_3D_Insect_Cricket_07.wav         (60 KB)
        │   ├── AMB_Forest_3D_Insect_Grasshopper_01.wav     (283 KB)
        │   ├── AMB_Forest_3D_Insect_Grasshopper_02.wav     (385 KB)
        │   ├── AMB_Forest_3D_Insect_Grasshopper_03.wav     (341 KB)
        │   ├── AMB_Forest_3D_Insect_Grasshopper_04.wav     (474 KB)
        │   ├── AMB_Forest_3D_Insect_Grasshopper_05.wav     (467 KB)
        │   ├── AMB_Forest_3D_Tree_Crack_01.wav              (298 KB)
        │   ├── AMB_Forest_3D_Tree_Crack_02.wav              (325 KB)
        │   ├── AMB_Forest_3D_Tree_Crack_03.wav              (350 KB)
        │   ├── AMB_Forest_3D_Tree_Crack_04.wav              (315 KB)
        │   ├── AMB_Forest_3D_Tree_Crack_05.wav              (277 KB)
        │   ├── AMB_Forest_3D_Tree_Crack_06.wav              (325 KB)
        │   ├── AMB_Forest_3D_Tree_Crack_07.wav              (392 KB)
        │   ├── AMB_Forest_3D_Tree_Crack_08.wav              (265 KB)
        │   ├── AMB_Forest_3D_Tree_Crack_09.wav              (361 KB)
        │   ├── AMB_Forest_3D_Tree_Rustle_01.wav             (898 KB)
        │   ├── AMB_Forest_3D_Tree_Rustle_02.wav             (1.2 MB)
        │   ├── AMB_Forest_3D_Tree_Rustle_03.wav             (1.7 MB)
        │   ├── AMB_Forest_3D_Tree_Rustle_04.wav             (1.9 MB)
        │   ├── AMB_Forest_3D_Tree_Rustle_05.wav             (2.2 MB)
        │   ├── AMB_Forest_3D_Tree_Rustle_06.wav             (2.1 MB)
        │   ├── AMB_Forest_3D_Tree_Rustle_07.wav             (1.9 MB)
        │   ├── AMB_Forest_3D_Tree_Rustle_08.wav             (1.6 MB)
        │   ├── AMB_Forest_3D_Tree_Rustle_09.wav             (2.1 MB)
        │   ├── AMB_Forest_3D_Water_Stream.wav               (4.3 MB)
        │   ├── AMB_Forest_3D_Wolf_Howl_01.wav              (1.1 MB)
        │   ├── AMB_Forest_3D_Wolf_Howl_02.wav              (1.5 MB)
        │   ├── AMB_Forest_3D_Wolf_Howl_03.wav              (1.7 MB)
        │   ├── AMB_Forest_3D_Wolf_Howl_04.wav              (2.1 MB)
        │   └── AMB_Forest_3D_Wolf_Howl_05.wav              (2.5 MB)
        │
        ├── FOL_FS_Debris/
        │   ├── FOL_FS_Debris_Dirt_01.wav    (142 KB)
        │   ├── FOL_FS_Debris_Dirt_02.wav    (146 KB)
        │   ├── FOL_FS_Debris_Dirt_03.wav    (158 KB)
        │   ├── FOL_FS_Debris_Dirt_04.wav    (161 KB)
        │   ├── FOL_FS_Debris_Dirt_05.wav    (192 KB)
        │   ├── FOL_FS_Debris_Grass_01.wav   (134 KB)
        │   ├── FOL_FS_Debris_Grass_02.wav   (144 KB)
        │   ├── FOL_FS_Debris_Grass_03.wav   (121 KB)
        │   ├── FOL_FS_Debris_Grass_04.wav   (98 KB)
        │   ├── FOL_FS_Debris_Grass_05.wav   (134 KB)
        │   ├── FOL_FS_Debris_Rock_01.wav    (101 KB)
        │   ├── FOL_FS_Debris_Rock_02.wav    (105 KB)
        │   ├── FOL_FS_Debris_Rock_03.wav    (108 KB)
        │   ├── FOL_FS_Debris_Rock_04.wav    (128 KB)
        │   ├── FOL_FS_Debris_Rock_05.wav    (113 KB)
        │   ├── FOL_FS_Debris_Sand_01.wav    (166 KB)
        │   ├── FOL_FS_Debris_Sand_02.wav    (142 KB)
        │   ├── FOL_FS_Debris_Sand_03.wav    (158 KB)
        │   ├── FOL_FS_Debris_Sand_04.wav    (173 KB)
        │   ├── FOL_FS_Debris_Sand_05.wav    (170 KB)
        │   ├── FOL_FS_Debris_Wood_01.wav    (101 KB)
        │   ├── FOL_FS_Debris_Wood_02.wav    (120 KB)
        │   ├── FOL_FS_Debris_Wood_03.wav    (98 KB)
        │   ├── FOL_FS_Debris_Wood_04.wav    (88 KB)
        │   └── FOL_FS_Debris_Wood_05.wav    (101 KB)
        │
        ├── FOL_FS_Water/
        │   ├── FOL_FS_Run_Water_Deep_01.wav     (160 KB)
        │   ├── FOL_FS_Run_Water_Deep_02.wav     (204 KB)
        │   ├── FOL_FS_Run_Water_Middle_01.wav   (195 KB)
        │   ├── FOL_FS_Run_Water_Middle_02.wav   (141 KB)
        │   ├── FOL_FS_Run_Water_Shallow_01.wav   (74 KB)
        │   ├── FOL_FS_Run_Water_Shallow_02.wav   (40 KB)
        │   └── FOL_FS_Run_Water_Shallow_03.wav   (97 KB)
        │
        ├── Gun/
        │   ├── Gun_AR_Tail/
        │   │   ├── Gun_AR_Tail_Field_Mid_01.wav   (436 KB)
        │   │   └── Gun_AR_Tail_Field_Mid_02.wav   (407 KB)
        │   │
        │   └── Gun_HG_Tail/                       (空目录)
        │
        └── (根目录音频)
            ├── water_deep.wav
            ├── water_middle.wav
            └── water_shallow.wav
```

## 统计

| 目录 | 文件数 | 说明 |
|------|--------|------|
| `assets/audio/` 根目录 | 12 | 氛围底噪、篝火、雷暴、风、人声、涉水 |
| `AMB_Forest/` | 24 | 森林环境（虫群、风、猫头鹰、蟋蟀、蚱蜢、树响、溪流、狼嚎） |
| `FOL_FS_Debris/` | 25 | 脚步碎片音（Dirt/Grass/Rock/Sand/Wood 各5） |
| `FOL_FS_Water/` | 7 | 涉水脚步音（Deep/Middle/Shallow） |
| `Gun/` | 2 | AR步枪远场尾音 |
| `Gun_HG_Tail/` | 0 | 空目录（手枪尾音预留） |
| `js/` | 8 | System1~4 前端代码 |
| 根目录 | 3 | index.html / serve.js / 启动脚本 |
| **合计** | **113** | **~115 MB** |

附：理论上，按照上述文件结构搭建系统后，音频加载应无异常。若运行中出现音频被程序化合成替代的情况，可能是音频文件缺失或其他环境问题所致。提交前我已逐一检查过素材完整性，但若仍有问题，您可查阅我通过微信和邮箱发送的完整未拆分版本。
