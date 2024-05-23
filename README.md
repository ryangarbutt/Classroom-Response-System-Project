# WSU CptS 322 Term Project SPRING SEMESTER 2023

Classroom Response System. Have a team build a classroom response system like iClicker or TopHat. Initial development could focus on the basic infrastructure, such as allowing instructors to design questions and allowing students to answer them. Subsequent development could greatly expand the features to include instructor and student dashboards, custom instruction types and even integration with LMSs. This will keep students participating in class and help teachers check student's understanding of the material

Collaborators:

	Ryan Garbutt				,	ryan.garbutt@wsu.edu
	
	Silvestre Pamatz-Rangel 		,	s.pamatz-rangel@wsu.edu
	
	Gabriel Allen				,	gabriel.allen@wsu.edu
	
	Yannik Castro				,	y.castro-morales@wsu.edu
	
	Xavier Smith				,	xavier.smith@wsu.edu
		
	Richard Castro				,	richard.castro@wsu.edu
	
	Joshua Yuan				,	joshua.yuan@wsu.edu
	

PROJECT SETUP:

If you are running the application on MAC OS in visual studio code, configure your default terminal language to bash
before running the code, make sure your terminal has been routed to the project folder
then you want to run these commands in this order: 
python3 -m venv venv
. venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
pip install wtforms[email]
pip install config 



If you are running the application on a Windows machine
navigate to the project folder
run these commands:
py -3 -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
pip install wtforms[email]
pip install config 
