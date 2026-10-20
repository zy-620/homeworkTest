# 作业提交说明

- 姓名：张屿
- 学号：2604020138
- 班级：26电子信息工程1班

## 目录结构

```
homework/
├── Project7/           编号-名称-单价 对齐表格输出
├── Project8/           1~5 英寸转厘米换算
├── Project11/          基本数据类型（int / float / double / char）
└── Project17/          个人简历表格（控制台字符画）
```

每个工程目录包含：源码 `.c`、`.vcxproj`、`.vcxproj.filters`、`.slnx` 解决方案文件，
用 Visual Studio 直接打开对应 `.slnx` 即可编译运行。

## 各题说明

| 工程 | 源文件 | 考点 |
| --- | --- | --- |
| Project7 | `Project7-表格输出.c` | `printf` 格式控制（`%6s`、`%-12s`、`%10.2f`）实现列对齐 |
| Project8 | `Project8-英寸转厘米.c` | 浮点运算与 `%.2f` 保留两位小数 |
| Project11 | `Project11-基本数据类型.c` | 四种基本数据类型定义与 `%d`、`%f`、`%c` 输出 |
| Project17 | `Project17-个人简历表格.c` | 控制台字符画排版、`SetConsoleOutputCP(65001)` 中文编码 |

## 备注

- 源文件名由模板默认的 `FileName.c` 改为带题意的名字，工程文件中的引用已同步更新。
- 仓库已添加 `.gitignore`，`.vs/`、`x64/`、编译产物不入库。
- 四个工程均已用 MSVC 编译并运行验证，输出正确。
