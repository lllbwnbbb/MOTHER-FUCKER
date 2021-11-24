h=float(input('请输入你的身高：（m）：'))
w=float(input('请输入你的体重（kg）：'))
b=w/(h乘h)  #计算bmi
if b<18.5:
    print('你的bmi指数为：'+str(bmi))
    print('体重过轻')
if 18.5<=b<24.9:
    print('你的bmi指数为：'+str(bmi))
    print('正常，继续保持')
if b>=29.9
