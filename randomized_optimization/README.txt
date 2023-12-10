### Instructions to setup environment to run code

* Download the ABAGAIL repo from github (https://github.com/pushkar/ABAGAIL)
"* Follow the instructions to download it and the other applications (Apache Ant, Java, etc)"
* Use the commands from the Wiki to test out some commands from command line (https://github.com/pushkar/ABAGAIL/wiki)
* I used Sublime Text Editor to update files and view the structure of the repo and files

### Part 1
* Ensure the BreastCancerTest.java file and breast cancer dataset are in the same location as Abalone test (in the src > opt > test location. 
* Open cmd line and change directory to the ABAGAIL directory and type: ant
"* Then, type this command: java -cp ABAGAIL.jar opt.test.BreastCancerTestTest"
* If you want to see the results with a different amount of iterations you can update the iteration count or any of the other parameters

### Part 2
* Run any of the tests listed with a similar command. Just update the end of the line.
* java -cp ABAGAIL.jar opt.test.TravelingSalesmanTest
* java -cp ABAGAIL.jar opt.test.ContinuousPeaksTest
* java -cp ABAGAIL.jar opt.test.KnapsackTest
