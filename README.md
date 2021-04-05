# python_input
入力など

# coding: utf-8
# 標準入力とループ処理
count = int(input())
#print("データ個数 " + str(count))
for i in range(count):
    line=input().rstrip()
    print(line + "は、スライムを攻撃した!")
    
入力した文字↓
4    #count用
勇者
戦士
僧侶
魔法使い
