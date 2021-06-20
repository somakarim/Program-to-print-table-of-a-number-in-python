# Program-to-print-table-of-a-number-in-python
table_of= input('Enter the number of table: ')
upto= input('Enter the number you need table upto: ')
for x in range(1, int(upto)+1, 1):
    print(int(table_of), ' X ', x, ' = ', int(table_of)*x)
