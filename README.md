# k8s-cicd
项目流水线发布程序

# 项目介绍
## 环境
### 前端
vue
### 后端
golang

## 功能
### 表格页
使用表格管理每个项目
每条信息： 流水线名称、别名、状态、创建时间、任务id， 功能操作：编辑、查看、运行、查看历史任务
状态和任务id的状态关联。
编辑：编辑流水线的信息，工作流，人员审批、步骤的操作记录、发布到k8s中
查看：一个workerflow的任务流程页面可以直观查看到最新任务的运行状况

