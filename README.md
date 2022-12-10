# separating-first-latter-of-a-stringuser_input=list(input("Enter here:- ").split(" "))
print(user_input)
Output=""
for i in user_input:
    u=i[0]
    u=u.upper()

Output=Output+" "+u+","
print(Output)
output=""
for i in user_input:
    f=i[1]+ " " + i[2:]+","
    output=output+" "+f
print(output)
