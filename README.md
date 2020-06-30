# Phython-Assigmemt-10 
  
[29/06, 7:21 pm]  names=["appu","sunny","simham","naksh"]
print(names)
print(names[0])
print(names[-3])
[29/06, 7:22 pm]  try:
	s=open("example.txt")
except:
	print("file can't be opened")
[29/06, 7:22 pm]  with open("example.txt") as s:
	print(s.read())
[29/06, 7:22 pm]  import os
if os.path.exists("example.txt"):
	os.remove("example.txt")
else:
	print("file doesn't exists")
[29/06, 7:23 pm]  s=open("example.txt")
data=s.readlines()
for line in data:
	x=line.split()
	print(x)
