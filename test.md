useCaseDiagram

    actor "普通用户" as User

    actor "管理员" as Admin



    %% 普通用户用例

    User --> (注册)

    User --> (登录)

    User --> (登出)

    User --> (修改个人信息)

    User --> (使用VIP兑换码)

    User --> (上传图片)

    User --> (编辑图片)

    User --> (删除图片)

    User --> (创建空间)

    User --> (管理空间成员)

    User --> (查看空间分析)

    User --> (浏览图片)

    User --> (搜索图片)

    User --> (以图搜图)

    User --> (按颜色搜索)

    User --> (创建AI扩图任务)

    User --> (查询扩图任务结果)

    User --> (发表评论)

    User --> (删除评论)

    User --> (点赞评论)

    User --> (关注用户)

    User --> (取消关注)

    User --> (查看关注列表)

    User --> (查看粉丝列表)

    User --> (点赞图片)

    User --> (系统自动增加浏览次数)

    User --> (查看未读评论)

    User --> (查看个人评论历史)



    %% 管理员用例

    Admin --> (管理用户)

    Admin --> (审核图片)

    Admin --> (批量编辑图片)

    Admin --> (管理评论)

    Admin --> (查看系统存储总览)
