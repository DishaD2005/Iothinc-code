# Iothinc-code
n=int(input('Enter amount of inputs:'))
for i in range(n):
    E=0
    F=0
    sentance=input('Enter the sentance:')
    for j in sentance:
        if j.lower() =='t':
            E=E+1
        if j.lower() =='s':
            F=F+1
    if E>F and 0<E<10000:
          print("English")
    if F>E and 0<F<10000:
           print("French")
        
