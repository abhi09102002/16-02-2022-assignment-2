def is_leap(year):
   if year%4==0 and year%100!=0 or year%400==0:
    return True
   else:
    return False

year = int(input())

OUTPUT:
1990
Your Output (stdout)
False
Expected Output

false
