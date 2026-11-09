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
