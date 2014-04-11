#def search_char(string,num):
    counter=0
    counter2=0
    counter3=0
    dumb=0
    ans=""
    string="(((AC)4B)2(DE)3)"
    num=4 
    while dumb != 1:
        if string[counter]==")" and string[counter+1]==num:
            counter2=counter
            while string[counter2] != "(":
                if string[counter2].isalpha()==true:
                    ans[counter3]=string[counter2]
                    counter3=counter3+1
                counter2=counter2-1
                if string[counter2]=="(":
                    return ans
        print string[counter]
        counter=counter+1
    
    
    

#string="(((AC)4B)2(DE)3)"
#num=4    
#print search_char(string,num)
