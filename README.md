takeout-test-jmeter/
├── README.md               # 项目说明（简历可贴该仓库地址）
├── script/                 # JMeter脚本目录
│   ├── main.jmx            # 主测试计划（全业务链路）
│   └── common/              # 公共复用片段
│       ├── login-token.jmx # 登录提取token公共脚本
│       ├── add-cart.jmx    # 加购物车片段
│       └── submit-order.jmx# 提交订单片段
├── data/                    # CSV测试数据
│   ├── 精确搜索/
│   │   └── actual_name.csv
│   ├── 模糊搜索/
│   │   └── 模糊搜索响应断言.txt
│   ├── 不存在搜索/
│   │   └── f_list.csv
│   ├── 加入购物车/
│   │   └── test_cart.csv
│   └── login/
│       ├── login.csv
│       └── ill_login.csv
