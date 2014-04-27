sendEmails
==========

This is code that send emails  


Funtion def send_email(message,subject,toaddrs) , connect to gmail account , that you define and sends email 


raw input stores in variables that that user type , here you can type, wher to send email, how many times, subject and message!

subject = raw_input("Enter your subject?\n")
message = raw_input("Enter your mesage?\n")
toaddrs = raw_input("Enter receiver email address?\n")
counter = raw_input("How many emails you want to send?\n")
for i in range(int(counter)):
    send_email(str(message),str(subject),str(toaddrs))
    
    
