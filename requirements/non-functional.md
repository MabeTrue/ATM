# 非功能需求

## 性能需求
    系统响应时间在2秒以内
    数据存储量在1G以上
    运行时限制：24小时全天候运行
    数据精度：精确到小数点后两位

## 基本设施需求

## 安全性需求

1. 考虑到操作安全，存取款以及转账的时间应该限定在1分钟以内。
2. 为了防止不法分子暴力破解密码，连续3次输错密码后，该账户将被临时冻结，需要客户本人携带身份证去营业厅解冻。
4. 用户进行操作前，需要先用密码进行用户身份的验证。
5. 该系统具有5年以上的使用寿命。
6. 系统能够长时间稳定，除非发生断电等意外。
7. 需要修改银行卡密码时，需要输入旧密码与身份证号进行验证后，才能修改。

## 软件质量属性

- 可靠性
     。。。。
- 易用性
     。。。。
- 可维护性
     。。。。

## 业务规则

- ATM机内没有钱时，则不能存款
- 每人每天转账金额不可超过10w人民币
- ATM机每天可存入的总金额为20w人民币，超过此值之后，只能取款，若需要存款可到银行营业厅。

## 用户文档