
![](resources/python.libs.2.png)

```py
import datetime

current_datetime = datetime.datetime.today()
current_date = datetime.date.today()
date_of_birth = datetime.date(1994, 4, 2)
my_age = current_date - date_of_birth

print("My age is %s" %(my_age))
print("My age in years is : %s" %(my_age.days/365))
print("My age in seconds is : %s " %(my_age.total_seconds()))
seconds = ((my_age.days/365) - (my_age.days//365)) * 86400
print("My age is %s years and %s seconds" %( my_age.days//365, seconds))
```