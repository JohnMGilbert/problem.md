John Gilbert

Steven Williams

Diego Morales

March 1, 2022

Problem Statement

Our team is going to develop software that helps an animal shelter distribute pet provisions by keeping an ever-changing database of recipients. Our customer, the Animal Action Program for Animals (herein referred to as APA) is a nonprofit organization that helps stray dogs and cats by giving them a chance to be adopted and avoid a kill-shelter. Providing lower-income pet owners with necessary pet care allows the owners to keep their animals. During the Covid pandemic a lot of animal owners lost their jobs, and the APA stepped in to help these families with giving then a certain amount of dog or cat food. This organization helps keep these animals alive so their owners will not drop their pet off at the pound or other kill shelters because they cannot afford to maintain care for the animals. The problem is the APA has insufficient data managements, and the necessary restrictions on the food distribution, which will be detailed below, is too hard to keep track of. Ultimately, we want to streamline the APA’s data management so they can more accurately maintain animal food-distribution.

The scope of the project is currently manageable. The three primary aspects are data manipulation, the GUI, and customer outreach. Instead of using an excel sheet and search for peoples names, we want to make a GUI that they can search for a persons name and that persons information will be read from the file and outputted to the screen for verification. We also want to make sure when you update the csv file it will write it out to a new csv as and updated file. At this facility you are only allowed to come and pick up dog and cat food 7 times in one year. We want to help this organization with keeping track and making sure that no one gets more then 7 rations so that the inventory can be manageable. The APA requires that to receive pet food, owners do not breed their animals. You can not join this program if your cat or dog is not spayed or neutered. In our GUI we are going to take this into consideration when it comes to new owners joining this program. We are also going to make sure that our GUI can handle data validation, and ensure that the program is saved by the user when any update is made. Should we need to make product sacrifices due to time constraints, we will sacrifice the GUI’s aesthetics, not it’s functionality. 

The base code is going to be centered around two objects, owners and animals. All necessary data will be held in these two objects. Time permitting, and if the customer desires it, we will also add functionality to view the amount of pet food distributed. We will store this data in a CSV file and feed that into the GUI. We are going to use javaFX to execute our GUI and this website gives us ideas on how we are going implement the GUI as well as some design ideas: https://openjfx.io/. 

Over the coming weeks, a team member will be corresponding with the APA to ensure that our product meets their needs. Although we currently have a good picture of the data we need, we want to ensure we don’t miss valuable consumer input and that the software we create preforms accurately on the machines the APA use. 
Our users are divided into two categories, admins and read-only. Currently the APA has two employers, and only one of them will be admin. The admin must enter a password and username in order to use the GUI’s write methods. The read-only user will be able to access the data for viewing should they need to validate a customer’s inquiries. While our system is not human life-critical, it has indirect implications on the lives of animals, therefore the data validation must be sound, and the accessing of the data must be totally and completely accurate. 

	The primary goal of this software is to allow for the customer to save time and resources by having a finely managed database that can be accessed and altered intuitively.

