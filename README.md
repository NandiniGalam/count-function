# count-function
#using count function
s=input()
ch=input()
c=0
5
for i in range(len(s)):
  if ch==s[i]:
    c=c+1 
print(c)
#approach 2
s=input()
v="aeiouAEIOU"
for i in range(len(s)):
  if s[i] not in v:
    print("no")
    break
  else:
    print("yes")



