# code-practice
代码练习合集
发工资案例

money =10000
for i in range(1,21):
    import random
    num = random.randint(1, 10)
    if num<5:
        print(f"员工{i}绩点{num}小于5，不发工资")
        continue
    if money >=1000:
        money -=1000
        print(f"员工{i}满足绩点发放1000元，总工资还剩{money}元")
    else:
        print("余额不足，下个月再发工资")

        break
