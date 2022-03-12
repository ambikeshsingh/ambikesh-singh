# ambikesh-singh
Banner Printing
Create Banner with the help of Python
***********************************************


def banner_text(text):
    Screen_width=100
    if len(text)>Screen_width-6: # 
        print("")
    if text=="*":
        print("*"*Screen_width)
    else:
        center_text=text.center(Screen_width-6)
        output_string="** {} **".format(center_text)   
        print(output_string)
banner_text("*")
banner_text("Always look on the bright side of life...")
banner_text("If life seems jolly rotten,")
banner_text("There's something you've forgotten!")
banner_text("And that's to laugh and smile and dance and sing,")
banner_text(" ")
banner_text("When you're feeling in the dumps,")
banner_text("Don't be silly chumps,")
banner_text("Just purse your lips and whistle - that's the thing!")
banner_text("And... always look on the bright side of life...")
banner_text("*")


result=banner_text("Nothing is return")
print(result)
