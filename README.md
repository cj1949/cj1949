## Hi there 👋

<!--
**cj1949/cj1949** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

day1 print（“hello world ”）
day1打卡
day2 import  random
num = random.randint(1, 10)
guess_num=int(input("蒙数："))
if guess_num == num:
    print("恭喜")
else:
    if  guess_num >=num:
        print("数大了")
    else:
        print("数小了")

    guess_num=int(input("再猜:"))

    if guess_num==num:
        if guess_num  >=num:
            print("大了")
        else:
            print("小了") 
day2打卡

money =10000
for i in range(1,21):
    import random
    score =random.randint(1,10)

    if score <5:
        print(f"员工{i}绩效分{score},不满足下一位")
        continue
    if money >=1000:
        money -= 1000
        print(f"员工{i},满足条件发,剩{money}")
    else:
        print(f"不够剩{money},不发了")
        break
day3打卡

num=5000000
name=None
name=input("输名字:")
def  query(show_header):
    if show_header:
        print("------余额------")
    print(f"{name},你好，余额剩:{num}元")
def saving(num):
    global money
    money += num
    print("-----存款-----")
    print(f"{name},你好，存款{num}成功")
    query(False)
def  get_money(num):
    global money
    money -= num
    print("-----取款-----")
    print(f"{name}你好取款{num}成功")
    query(False)
def main ():
    print("----主菜单----")
    print(f"{name},你好欢迎请选择操作")
    print("查余额\t[输1]")
    print("存款\t[输2]")
    print("取款\t[输3]")
    print("退出\t[输4]")
    return  input("输入选择：")
while  True:
    keyboard_input = main()
    if keyboard_input == "1":
        query(True)
        continue
    elif keyboard_input == "2":
        num = int(input("存多少输入："))
        saving(num)
        continue
    elif keyboard_input == "3":
        num = int(input("取多少输入："))
        get_money(num)
        continue
    else:
        print("退出了")
        break
day4打卡

print("World is beautiful")
day5打卡

print(f"a大于A，结果：{"a">"A"})
day6打卡

print(f"ab”大于“a”，结果：{"ab">"a"})
day7打卡
