
![](resources/python.libs.4.png)

```py
import csv

#Write
with open('file.csv', 'w', newline='') as csvfile:
    csv_writer = csv.writer(csvfile)
    csv_writer.writerow(['Spam', 'Lovely Spam', 'Wonderful Spam'])

# Read
with open('file.csv') as csvfile:
    reader = csv.reader(csvfile)
    for row in reader:
        print(row)
        print(" ".join(row))

```