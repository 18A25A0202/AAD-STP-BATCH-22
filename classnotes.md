
Good Evening to all
------------------
Day-2
-------------------
Day-Objectives:
--------------------
1.Project Structure

2.How to Enable Developer Options In out Mobile

3.View And View Group

4.Android App Components.

5.How to run an HelloWorld Programm in our Mobile

java file

android-java file-activity file

android-xml-layout file

R.java


setcontentview(R.layout.activity_main)

Mainfest:

it can be give the permissions

example:INTETNET,LOCATION,INTERNAL_STORAGE

<uses-permission android:name="android.permission.INTERNET"/>

APPLICATION STRUCTURE:
----------------------
ANDROID-XML+JAVA

<Mainfest>

<give permissions>

<APPLICATION
name
icon
>
<Activity>
<Intent_Filter>
<java file>+<xml file>
</Intent_Filter>
</Activity>
</APPLICATION>

</Mainfest>

xml-screen design

Activity-implement the onclick events

10-9-2020 class notes


onclick listeners:
------------------

1.by using xml file

2.by using java file

1.by using xml file

<Li
w
h
o>
<Button
android:onclick="toastname"--alr+enter
w
h
/>
<Textview/>
<Button
android:"@+id/count"

/>
</Li>

How to create the method:
--------------------------

public void methodname(View view)
{

}

example:
---------
public void toastname(View view)
{

}

Steps to Implements Method Declaration in MainActivity:
----------------------------------------------
1.global declaration variable for particular view

Button co;

2.we have to get the id for oncreate() method
with the help of findviewbyId()

co=findviewbyId(R.id.count);

co.setOnclicklistener(new Onclicklistener)

{

   public void onclick(View view)
   {
   
   }

}

How to declare the toast message in or android:
----------------------------------------

Toast is a one of the class

we have to write an toast with the

help Toast


Syntax for Toast Class:
------------------------

Toast.maketext(context,string,duration).show();

Example:
--------
activity_main.xml

MainActivity

Toast.maketext(this
                MainActivity.this,
				getapplicationContext,
				"VAMANAPALLI GOPAL",
				Toast.LENGTH_LONG
				Toast.LENGTH_SHORT).show();





















