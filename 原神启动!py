import random

while True:
    user_input = input("请输入一些文字：")

    responses = []

    keywords1 = [
        "原神", 
        "提瓦特", 
        "派蒙"
        ]

    for keyword in keywords1:
        if keyword in user_input:
            responses.extend([
                "我超 原！",
            ])
            
    keywords2 = [
        "华为", 
        "鸿蒙", 
        "国产", 
        "5g"
        ]
    
    for keyword in keywords2:
        if keyword in user_input:
            responses.extend([
            "先有华为后有天，4G手机卖九干，我拿华为当国货，华为把我当大佐。不买华为是汉奸，开上鸿蒙如升仙，唯有华为是国产，谁说不好谁汉奸。",
            "先有华为后有天，疏油闪存绿光边,莱卡三摄秒单反，浴霸炮筒炸神仙。海军余威震天响，海思麒麟傲人间。华而不实任我为，不买你就是汉奸。"
        ])

    if responses:
        response = random.choice(responses)
        print(response)
    else:
        print("。。。")
