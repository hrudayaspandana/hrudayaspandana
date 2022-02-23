- 👋 Hi, I’m @hrudayaspandana
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
hrudayaspandana/hrudayaspandana is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
l=[]
n=int(input('enter n'))
for i in range (n):
    e=int(input())
    l.append(e)
min=l[0]
for i in range (1,n):
    if l[i]<min:
        min=l[i]
print('min num is',min)
max=l[0]
for i in range (1,n):
    if l[i]>max:
        max=l[i]
print('max num is',max)
