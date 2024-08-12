# Insert-Delete-to-from-Array
# Inserting and Deleting data in Array
import array
data=array.array('f',[])
while True:
 print('1. add numbers')
 print('2. delete numbers')
 print('3. view data')
 print('4. exit')
 ch=int(input('enter your choice'))

 if ch==1:
  a=int(input('enter index value: '))
  b=int(input('enter data value: '))
  data.insert(a,b)

 elif ch==2:
  a=int(input('enter index value: '))
  data.pop(a)
  print(a,'index deleted!')
 elif ch==3:
  print(data)
 elif ch==4:
  exit(0)
 else:
  print('Invalid choice!')
