counter=0
counter2=0
counter3=0
dumb=0
ans=""
string="(((AC)4B)2(DE)3)"
num=4
while counter+1<len(string):
    if string[counter]==")" and string[counter+1]==num:
        while string[counter] != "(":
            if string[counter].isalpha()== True:
                ans[counter3]=string[counter]
                counter3 += 1

            if string[counter]=="(":
                print ans
                break
            counter -= 1
    counter += 1
