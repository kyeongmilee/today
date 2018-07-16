import datetime
now = datetime.date.today()
name = raw_input("what is your name~~??")

s="hello,["+name+]! Today is [%02d/%02d/%04d]."%(now.month, now.day, now.year)
print s
