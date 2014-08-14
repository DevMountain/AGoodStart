AGoodStart
==========

The very first project for iOS pre-course.

### Let's get started

*Note: Feel free to use either language (Swift or Objective-C) for the pre-course projects. Base projects will be included for each.*

You also have 2 options with each project. You can create a project from scratch and push it to your GitHub account on your own, or you can fork the repositories we provide and update them with your code.

### Step 1: Download Xcode
- Gotta have Xcode. If you don't, go download it from the App Store now. It doesn't matter if you're using 5 or 6, but we'll use 6 in class. 

### Step 2: Start your project
#### Option 1: Create the project in Xcode
- In the launch view of Xcode click Create A New Project or click File->New->New Project
- Store it in a 'code' folder (*developer hint*)
- We actually only care about an Empty application for the next few projects. Xcode 6 removes this option, so you can create a Single View Application if you want.
- In GitHub create a repository on your account called AGoodStart
- Xcode already created the repository for you, and created an initial commit
- Navigate to the project folder via terminal (here is a [tutorial](http://computers.tutsplus.com/tutorials/navigating-the-terminal-a-gentle-introduction--mac-3855) if you don't know how)
- Get the https url on the right side of your project window
- Then add the remote repository and push to it:
``` git remote add origin git@example.com:my_project.git [this is your project url]
``` git push -u origin master

#### Option 2: Clone this project down to your computer
- In GitHub click the "Fork" button on the upper right corner of this project
- Navigate in terminal to where you want to put the project (hopefully a special folder just for 'code')
- Get the https url on the right side of your project window
- Then clone down the folder:
``` git clone git@example.com:my_project.git my_project
``` cd my_project

### Step 3: Hello World
- You should have an AppDelegate file to work with (.swift or .m file is where we'll be working)
- You may wonder where to write code. When the application finishes launching it will start in the AppDelegate and call the "didFinishLaunchingWithOptions" method. You'll put code in there.
- In the AppDelegate file add a line to print the words "Hello World" to the console.
- Commit and push your code to GitHub
``` git add .
``` git commit -m “Add log Hello World”


*Note: Feel free to use a GUI application for Git. I love Tower (it is expensive), and a lot of the students have used the free [GitHub app](http://mac.github.com).
