<h1 align="center"> Patient Monitoring System </h1>
<p align="center"> <img src="https://user-images.githubusercontent.com/103469969/209050078-d8483086-c632-48ec-a8b6-ccaf9ef361bb.png" style="width: 150px; height: 150px"> </p>

<p align="center"> Made for the Ateneo de Davao School of Nursing (ADDU-SON) </p>

## Table of Contents
1. [Project Description](#project-description)
2. [Purpose and Details](#purpose-and-details)
3. [Frameworks](#frameworks)
4. [Sub-systems](#sub-systems)

## Project Description
> <p align="justify"> A patient monitoring system is a set of systems and/or processes that enable medical professionals to monitor a patient's health. These systems are mostly used for remote patient monitoring and are also referred to as remote physiologic monitoring. </p>

## Purpose and Details
> <p align="justify"> This project is primarily used for nursing students and nursing personnel to practice and to survey monitoring critical details like calculating ECG, respiration, blood pressure and body temperature. It will record and log each detail according to the names of the patient, and will update the record in real-time. Once recorded, all of the details will be stored onto the database and can be printed out through a table, and ready to be received by the patient. </p>

## Frameworks
> <p align="justify"> The project is created using these frameworks: </p>

* [Laravel](https://laravel.com/) <img src="https://user-images.githubusercontent.com/103469969/209066598-90d55001-2dbe-4bc4-b2f9-43426696399f.png"
style="width: 20px; height: 20px">
  * <p align="justify"> Laravel is an open-source PHP framework, offering the rich set of functionalities that incorporates the basic features of PHP frameworks such as CodeIgniter, Yii, and other programming languages like Ruby on Rails. </p>
 
* [Breeze-Vue](http://breeze.github.io/doc-main/) <img src="https://user-images.githubusercontent.com/103469969/209067448-7e679621-a4d1-4ec7-b70f-b75625f8f62c.png"
style="width: 20px; height: 20px"> <img src="https://user-images.githubusercontent.com/103469969/209067451-dce617b6-14fe-4210-9837-885a1dbed693.png" style="width: 20px; height: 20px">
  * <p align="justify"> Breeze and Vue are JavaScripts libraries that help you manage data in rich client     applications, and a progressive framework that build user interfaces respectively. </p>

* [MySQL](https://www.mysql.com/) <img src="https://user-images.githubusercontent.com/103469969/209067913-15a142ec-a1fd-4409-83da-ee0505656b23.png" style="width: 20px; height: 20px;">
  * <p align="justify"> MySQL is a realtional database management system (RDBMS) developed by Oracle that is based on structured query language (SQL). </p>


## Sub-systems
> <p align="justify"> For the project to function normally, it requires these three general components:
* **Patient monitoring device** 
  
  * <p align="justify"> This is the part of the device that comes incontact with or is inserted into the patient. </p>
  * <p align="justify"> Usually includes a sensor that digitizes the information and a processing device that collects the     data and prepares it for analysis. </p>

* **User access portal**
 
  * <p align="justify"> This is used to collect data and to store in the database. </p>
  * <p align="justify"> As the program collects health data, it will be sent to either a local data collection devices, or   a remote cloud, ready to be compiled into useful information. </p>

* **Software**
  
  * <p align="justify"> Both the device and the portal will be utilized through software. </p>
  * <p align="justify"> It is extremely important as the software translates the information from its hardware so it can be     understood and used by medical professionals. </p>
