# 日报生成工具
一款基于python编写的日报生成工具，自定义日常工作内容进行随机抽取生成。

运行软件生成配置文件，对如下内容进行修改，填入自己日常工作的内容，每个group下随机抽取3条进行生成。
{
    "group1": {
        "description": "已经完成的工作",
        "tasks": [
            "完成项目A的任务1",
            "完成项目B的任务2",
            "完成项目C的任务3",
            "完成项目C的任务4",
            "完成项目C的任务5",
            "完成项目C的任务6",
            "完成项目C的任务7",
            "完成项目C的任务8",
            "完成项目C的任务9",
            "完成项目C的任务10"
        ]
    },
    "group2": {
        "description": "还在支撑的工作",
        "tasks": [
            "支撑项目A的任务1",
            "支撑项目B的任务2",
            "支撑项目C的任务3",
            "支撑项目C的任务4",
            "支撑项目C的任务5",
            "支撑项目C的任务6",
            "支撑项目C的任务7",
            "支撑项目C的任务8",
            "支撑项目C的任务9",
            "支撑项目C的任务10"
        ]
    },
    "group3": {
        "description": "计划开展的工作",
        "tasks": [
            "开展项目A的任务1",
            "开展项目B的任务2",
            "开展项目C的任务3",
            "开展项目C的任务4",
            "开展项目C的任务5",
            "开展项目C的任务6",
            "开展项目C的任务7",
            "开展项目C的任务8",
            "开展项目C的任务9",
            "开展项目C的任务10"
        ]
    }
}

单日生成的日报：
 2024.12.04 日报 星期三

 已经完成的工作:
1. 完成项目C的任务4
2. 完成项目C的任务6
3. 完成项目C的任务10

 还在支撑的工作:
1. 支撑项目C的任务4
2. 支撑项目C的任务9
3. 支撑项目B的任务2

 计划开展的工作 (2024.12.05):
1. 开展项目C的任务9
2. 开展项目C的任务10
3. 开展项目C的任务6

批量生成的日报：
======== 2024.12.02 日报 ========
 2024.12.02 日报 星期一

 已经完成的工作:
1. 完成项目C的任务9
2. 完成项目B的任务2
3. 完成项目C的任务4

 还在支撑的工作:
1. 支撑项目C的任务3
2. 支撑项目C的任务4
3. 支撑项目C的任务6

 计划开展的工作 (2024.12.03):
1. 开展项目A的任务1
2. 开展项目C的任务8
3. 开展项目C的任务9

======== 2024.12.03 日报 ========
 2024.12.03 日报 星期二

 已经完成的工作:
1. 完成项目A的任务1
2. 完成项目C的任务6
3. 完成项目C的任务4

 还在支撑的工作:
1. 支撑项目C的任务10
2. 支撑项目C的任务7
3. 支撑项目A的任务1

 计划开展的工作 (2024.12.04):
1. 开展项目C的任务6
2. 开展项目C的任务8
3. 开展项目C的任务9

======== 2024.12.04 日报 ========
 2024.12.04 日报 星期三

 已经完成的工作:
1. 完成项目C的任务3
2. 完成项目C的任务5
3. 完成项目C的任务6

 还在支撑的工作:
1. 支撑项目C的任务4
2. 支撑项目C的任务9
3. 支撑项目C的任务3

 计划开展的工作 (2024.12.05):
1. 开展项目C的任务10
2. 开展项目C的任务8
3. 开展项目C的任务4


自动跳过星期天。
