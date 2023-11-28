import time

def send_love():
    print("亲爱的，我想告诉你一个小秘密...")
    time.sleep(2)
    print("其实，我喜欢你很久了！")
    time.sleep(2)
    print("你总是让我心动不已，每次看到你都有一种特别的感觉。")
    time.sleep(2)
    print("我喜欢你的笑容，喜欢和你在一起的时光。")
    time.sleep(2)
    print("愿意成为你生命中的那个特别的人。")
    time.sleep(2)
    print("如果你也喜欢我，能不能...答应我？")
    time.sleep(2)
    print("愿意和我在一起吗？（输入Y或N）")

response = input("请输入你的回答：")
if response.lower() == 'y':
    print("太好了，我真的很开心！")
else:
    print("哦，没关系，谢谢你诚实回答。希望我们还是可以做好朋友。")
