STEP 1: Run the Jar file
`````````````````````````
On starting the java application for the first time, it asks the administrator to set up an Admin
password
 .. image::
   https://raw.github.com/raehasandalwala/Project-Reports/master/Video%20Chat/images/s1.png
   
**STEP 2: Set up Admin password**
```````````````````````````````
• Case 1: If there is a password Mismatch then a dialog box shows up as shown
 .. image::
   https://raw.github.com/raehasandalwala/Project-Reports/master/Video%20Chat/images/s2.png
• Case 2: If Exit using Close button on the right upper corner the application stops and on
restarting again asks to set the Admin password
• Case 3: If Admin password is correctly set up then the Server Main Frame opens
 .. image::
   https://raw.github.com/raehasandalwala/Project-Reports/master/Video%20Chat/images/s3.png
   
NOTE: At any point of time if you close the application and restart the application after setting
up the password, the Admin Login Window appears.


THE MAIN SERVER FRAME

The server frame consists of 3 panels :

SERVER PANEL

The server panel has a server log and three buttons namely :

#. Start Server

#. Setup server

#. Save and Clear log

It also contains a server log which keeps track of the operations and requests honoured
and denied by the server.

On clicking the start server button

Two things can happen:

• Case 1 : if you haven’t setup a server then on clicking start server, the log shows
messages as follows:

“ERROR: Table ‘userdetails.address’ doesn’t exist”

• Case 2: if u don’t have the required mysql driver then error log comes as:

“ERROR missing ‘com.mysql.jdbc’ driver”

To get rid of these errors the admin must set up the server first to do so click on Setup
Server button

**STEP 3: Setting up the mysql server connection**
````````````````````````````````````````````````
On clicking the setup server button following screen opens up.

.. image::
   https://raw.github.com/raehasandalwala/Project-Reports/master/Video%20Chat/images/s4.png
   
The admin has to fill the informations about the server correctly, so as to connect with the
mysql server through JDBC otherwise the previous errors would persist after proiding the
correct details press the save button

• and then click the create database button and the create Table button

• now click on the close button to return to the server main frame

• observer that the previously coming errors on the server log has stopped

• clear the log by pressing the Save and Clear log button to refresh the log

NOTE: At any point of time if you close the application and restart the application after setting
up the password, the Admin Login Window appears

STATUS PANEL

Unless any user is registered by the Admin the panel looks like

.. image::
   https://raw.github.com/raehasandalwala/Project-Reports/master/Video%20Chat/images/s5.png
   
The upper part shows the registered and online users and the lower part shows the registered but
offline users.

.. image::
   https://raw.github.com/raehasandalwala/Project-Reports/master/Video%20Chat/images/s6.png

To see this functionality let us register a user.

**STEP 4: User Registration**
`````````````````````````````
The Registration panel holds two fields in which username and password could be set for a
client.

It also has 4 buttons

#. Save

#. Delete

#. Kick

#. View Database

On clicking the save button following things can happen

• Case 1: If no username is given a dialog box comes as shown below
.. image::
   https://raw.github.com/raehasandalwala/Project-Reports/master/Video%20Chat/images/s7.png
   
• Case 2: If no password was selected a dialog box comes as shown below
.. image::
   https://raw.github.com/raehasandalwala/Project-Reports/master/Video%20Chat/images/s8.png
• Case 3: If a username already exists a dialog box comes as shown below
.. image::
   https://raw.github.com/raehasandalwala/Project-Reports/master/Video%20Chat/images/s10.png
• Case 4: If unique username and a password is given
.. image::
   https://raw.github.com/raehasandalwala/Project-Reports/master/Video%20Chat/images/s11.png
a dialog box comes as shown below

.. image::
   https://raw.github.com/raehasandalwala/Project-Reports/master/Video%20Chat/images/s12.png
   
**On clicking the delete button**

• Case 1: If inappropriate username is given a dialog box comes as shown below

.. image::
   https://raw.github.com/raehasandalwala/Project-Reports/master/Video%20Chat/images/s13.png
   
Password is not required to be given

**On clicking the kick**

• Case 1: If inappropriate username is given a dialog box comes as shown below

.. image::
   https://raw.github.com/raehasandalwala/Project-Reports/master/Video%20Chat/images/s13.png
   
• Case 2: If unregistered name was given a dialog box comes as shown below

.. image::
   https://raw.github.com/raehasandalwala/Project-Reports/master/Video%20Chat/images/s14.png
   
• Case 3: If registered name was given a dialog box comes as shown below

.. image::
   https://raw.github.com/raehasandalwala/Project-Reports/master/Video%20Chat/images/s16.png
   
**STEP 5: View The Databse**
```````````````````````````
On clicking the View Database Button the present state of the table can be viewed by the
admin.

**STEP 6: ADMIN LOGIN AND PASSWORD CHANGE**
`````````````````````````````````````````
.. image::
   https://raw.github.com/raehasandalwala/Project-Reports/master/Video%20Chat/images/s17.png
   

On starting the java application for the second time given the fact that the admin password has
been set up, it asks the administrator to login as Admin by giving the Admin password.

• Submit Button Functionality

Case 1: If the password is wrong then a dialog box shows up as shown

.. image::
   https://raw.github.com/raehasandalwala/Project-Reports/master/Video%20Chat/images/s18.png
   
Case 2: If Exit using Close button on the right upper corner the application stops and
on restarting again asks for Admin password

Case 3: If Admin password is correctly given then the Server Main Frame opens

.. image::
   https://raw.github.com/raehasandalwala/Project-Reports/master/Video%20Chat/images/s19.png
   
• Change Password Button Functionality:
If the change password button is clicked, following frame opens up

.. image::
   https://raw.github.com/raehasandalwala/Project-Reports/master/Video%20Chat/images/s20.png
The user has to enter the old password, then the new password and at last confirm the old
password and press on submit On clicking following things can happen:

Case 1: If old password is wrong then message comes

.. image::
   https://raw.github.com/raehasandalwala/Project-Reports/master/Video%20Chat/images/s21.png
   
Case 2: If confirmed password didn’t match the new password then message appears

.. image::
   https://raw.github.com/raehasandalwala/Project-Reports/master/Video%20Chat/images/s22.png
   
Case 3: All fields are correct and the message appears:

.. image::
   https://raw.github.com/raehasandalwala/Project-Reports/master/Video%20Chat/images/s23.png
And opens the admin login again.

On submitting the new password the server frame opens up, 
Follow Step 2;
