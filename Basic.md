1）KMS 是什么服务？能解决什么问题？
Key Management Service
是一项托管服务，加密数据的加密密钥

2）使用 KMS key 的方式有哪些？
生成适用于加密应用程序的随机数
使用非对称 CMK 对消息进行签名和验证
使用对称或非对称 CMK 对数据进行加密、解密和重新加密

3）可以对 KMS key 进行哪些操作？（至少 5 个）
[创建](https://docs.aws.amazon.com/zh_cn/kms/latest/developerguide/create-keys.html)
[编辑](https://docs.aws.amazon.com/zh_cn/kms/latest/developerguide/editing-keys.html)
[对称和非对称 CMK](https://docs.aws.amazon.com/zh_cn/kms/latest/developerguide/symmetric-asymmetric.html)
[查看](https://docs.aws.amazon.com/zh_cn/kms/latest/developerguide/viewing-keys.html)
[密钥策略](https://docs.aws.amazon.com/zh_cn/kms/latest/developerguide/key-policies.html)
[删除 CMK](https://docs.aws.amazon.com/zh_cn/kms/latest/developerguide/deleting-keys.html) 