简单的学科竞赛管理系统(SpringBoot3+vue3)
 1.系统采用Redis+JWT+Spring Security的技术组合来实现了用户认证和授权机制；
2.当手动注册时，需要提供邮件，邮件服务可能会有些耗时，采用RabbitMq进行邮件的分发；
3.管理员端：轮播图管理、竞赛管理、教师管理和学生管理四个功能模块，其中竞赛管理又包含了竞赛审核，竞赛信息
管理和竞赛成绩管理，竞赛成绩管理可以对学生成绩进行修改或者对成绩进行Excel表格的导出；
4.学生端包含了竞赛信息查询、竞赛报名查询、个人信息管理、竞赛成绩查询、竞赛作品文件上传等功能，还可以使用
富文本发表论坛；
5.教师端提供了个人信息管理、竞赛申请、竞赛审核查询、竞赛评分以及竞赛成绩导出功能，
