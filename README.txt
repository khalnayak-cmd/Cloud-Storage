# ---------------------------------------------------------------------------- #
#      Works Best with XAMPP server, it's Recommended to use XAMPP server      #
# ---------------------------------------------------------------------------- #


# ---------------------------------------------------------------------------- #
#                                 Key Features                                 #
# ---------------------------------------------------------------------------- #

1. Send OTP through Email
2. Removed PHP extension from url
3. 404 Error Handling
4. Responsive, Works Fine with mobile devices also
5. simple and secure

# ---------------------------------------------------------------------------- #
#                              important to setup                              #
# ---------------------------------------------------------------------------- #

to use the Cloud Storage mini project you have to setup some things.

1. Create a folder called
	cloud storage      
inside c:/xampp/htdocs/cloud storage/

2. decompress the zip file and paste inside the cloud storage 
	e.g: c:/xampp/htdocs/cloud storage/index.php


3. smtp server, you have to setup your smtp server in your php.ini file and sendmail/sendmail.ini
    visit this to tutorial https://stackoverflow.com/questions/15965376/how-to-configure-xampp-to-send-mail-from-localhost#answer-18185233

4. edit the forgotpass.php file in line 33
    $headers = "from:NS Cloud Storage <Your Email Address>\r\n";  // change this to

    //this 
    $headers = "from:NS Cloud Storage <abc@gmail.com>\r\n";

5. you have to use only gmail smtp server because it's free you can also use paid servers

# ---------------------------------------------------------------------------- #
#                                    DB part                                   #
# ---------------------------------------------------------------------------- #

6. Create database called 'cloudstorage' you can check conn.php file for confirmation

7. Add table called 'login_info' case sensitive underscore required

8. Create Fields respectively
    id (primary key  and  Auto increment is compulsory)
    name
    username
    email 
    password


Thank you!
