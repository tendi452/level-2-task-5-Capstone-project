# level-2-task-5-Capstone-project
import sqlite3 

db = sqlite3.connect('data/ food_db)
cursor = db.cursor(menu) 

cursor.execute('''
       CREATE TABLE menu(id INTERGER PRIMARY KEY, name TEXT, price INTERGER)
''') 

db.commit 

cursor = db.cursor()
food1 = 'Pizza'
price1 = 45 

food2 = 'Chips'
price2 = 30 

cursor.execute('''INSERT INTO menu(food, price)
                  VALUES(?,?)''', (food1, price1))
print( first user inserted)

cursor.execute('''INSERT INTO menu(food, price)
              VALUES(?, ?), (food2, price2))
print(second user inserted)

db.commit()


id = lastrowid 
id = 1
cursor.execute = ('''SELECT food, price FROM menu WHERE id = ?''', (id, )
menu = cursor.fetchone()
print('Pizza', price)

price = 80 
id = 1 
cursor.execute('''UPDATE menu SET price = 80 WHEREid = 1,  ( 'Pizaa', 45)
print('menu data updated!')

print('SELECT food, price FROM menu: ') 
cursor.execute('''SELECT food, price FROM menu''')
for row in cursor :
        print({0}: {1})', format('row[0], row[1])

cursor.execute('''DROP TABLE menu''')
print('menu table deleted!''')

db.commit()
db.close()
print("connection to database closed)

        
