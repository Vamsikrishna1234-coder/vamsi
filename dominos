od=[]
ch1='y'
while ch1=='y':
     print('DOMINOS PIZZA HUT')
     print('menu')
     print('1.pizza')
     print('2.chicken popcorn')
     print('3.pasta')
     print('4.burger')
     print('5.cake')
     print('6.Limca')
     ch=int(input('enter item'))
     if(ch>=1 and ch<=6):
         print('valid input')
         if(ch==1):
            od.append('pizza')
         elif(ch==2):
             od.append('chicken popcorn')
         elif(ch==3):
             od.append('pasta')
         elif(ch==4):
             od.append('burger')
         elif(ch==5):
             od.append('cake')
         elif(ch==6):
             od.append('Limca')
     else:
          print('not valid')

     ch1=input('DO you want to continue(y/n):',)
print('your orders are:',od)
ch1=input('Do you want to modify(y/n):',)
print('1.add item')
print('2.Delete item')
print('3.modify item')
ch=int(input('enter any number'))
if(ch>=1 and ch<=3):
    if(ch==1):
        while ch1== 'y':
               print('1.pizza')
               print('2.chicken popcorn')
               print('3.pasta')
               print('4.burger')
               print('5.cake')
               print('6.Limca')
               ch=int(input('enter any number'))
               if(ch>=1 and ch<=6):
                  if(ch==1):
                     od.append('pizza')
                  elif(ch==2):
                     od.append('chicken popcorn')
                  elif(ch==3):
                     od.append('pasta')
                  elif(ch==4):
                     od.append('burger')
                  elif(ch==5):
                     od.append('cake')
                  elif(ch==6):
                     od.append('Limca')
               else:
                   print('pls check the menu name')

               ch1 = input('Do you want to continue(y/n):',)
        print('your orders are:',od)
    elif(ch==2):
        print('your order are:',od)
        item=input('enter item name')
        if (item in od):
            od.remove(item)
            print('your item is deleted')
            print('your orders are:',od)
        else:
             print('!..sorry item not available')
             print('your orders are:',od)
    else:
        print('your orders are:',od)
        modify=input('enter item name')
        if modify in od:
            new=input('enter new item')
            i=od.index(modify)
            print('available in index number is:',i)
            od[i]=new
            print('your orders are:',od)
        else:
            print('!..sorry item not available')
            print('your orders are:',od)

else:
    print('enter valid number')
