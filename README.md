# CS311
Assignment no 1
<?xml version="1.0" encoding = "UTF=8"?>
<!-- Root ELEMENT Online Study Portal -->
<!DOCTYPE Online_Study_Portal[
<!-- Child ELEMENT of Online Student Enroll are Student and Enroll -->           
<!ELEMENT Online_Study_Portal(Student+,Enroll+)>
<!-- Child ELEMENT of Enroll -->
<!ELEMENT Enroll(CompilerConstruction,ComputerGraphics,DataStructures,AndroidDevelopment,WebProgramming)>
<!ELEMENT CompilerConstruction(#PCDATA)>
<!ELEMENT ComputerGraphics(#PCDATA)>
<!ELEMENT DataStructures(#PCDATA)>
<!ELEMENT AndroidDevelopment (#PCDATA)>
<!ELEMENT WebProgramming (#PCDATA)>
<!-- Attributes of Student -->
<!ATTLIST Student Id Id #REQUIRED>
<!ATTLIST Student Name CDATA #REQUIRED>
<!-- Attributes of CompilerConstruction -->
<!ATTLIST CompilerConstruction courseid CDATA #REQUIRED>
<!-- Attributes of ComputerGraphics -->
<!ATTLIST ComputerGraphics courseid CDATA #REQUIRED>
<!-- Attributes of DataStructures -->
<!ATTLIST DataStructures courseid CDATA #REQUIRED>
<!-- Attributes of AndroidDevelopment -->
<!ATTLIST AndroidDevelopment courseid CDATA #REQUIRED>
<!-- Attributes of WebProgramming -->
<!ATTLIST WebProgramming courseid CDATA #REQUIRED>]>
<Online_Study_Portal>
	<Student Id="BC160402347" Name="Fahim">
		Id: BC160402347<br/>
		Name: Fahim ud din<br/>
	</Student>
	<Enroll>
		<CompilerConstruction courseid="cs301">
			Compiler Construction<br/>
		</CompilerConstruction>
		<ComputerGraphics courseid="302">
			Computer Graphics<br/>
		</ComputerGraphics>
		<DataStructures courseid="303">
			Data Structures<br/>
		</DataStructures>
		<AndroidDevelopment courseid="304">
			Android Development<br/>
		</AndroidDevelopment>
		<WebProgramming courseid="305">
			Web Programming<br/>
		</WebProgramming>
	</Enroll>
</Online_Study_Portal>
