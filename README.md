# MAD-2018
HHS Mobile App Development

*By Eric Cheng, David McAllister, and Lily Li*

Check out more details on our wiki: https://github.com/Eric-Cf/MAD-2018/wiki

This app is designed to provide a mobile interface that works alongside a stable backend database structure to provide users with information about available books, their holds, and their checkouts. Additionally, it implements a scanner API to allow users to checkout books with their phone cameras. The app was developed in conjunction with Homestead High School's library to ensure our app would be useful in a real world situation.

## Getting Started

Download Xcode to run the testing environment. You can view the code, but you need a developer account to sign the instance to run on your computer. 
Alternatively, you can download the app off of "TestFlight" onto your phone to run the app on your phone.

### Prerequisites

To view the code
```
-Mac OS
-XCode
```
To run the application on your computer
```
-Mac OS
-XCode
-Developer signing 
```

### Installation and Use

A step by step series of how to run our project assuming prerequisites are met.
**Click any of the steps to view an image example of the step**

1. [Open Xcode](Pictures/Proj1.png)
2. [Locate the submission folder and enter the MAD folder inside, clicking on the MAD.xcworkspace file](Pictures/Proj2.png)
3. [After clicking open, click on the uppermost blue MAD file. You may see some red errors](Pictures/Proj3.png)
4. [Change the provisioning profile to your own developer account](Pictures/Proj4.png)
5. [It might say “Failed to create provisioning profile”](Pictures/Proj5.png)
6. [Edit the bundle identifier by adding a number to the end and click “Try Again”](Pictures/Proj6.png)
7. [You can now view all the classes and storyboards that go into the application](Pictures/Proj7.png)
8. [Make sure xcode is creating a simulator of a valid iphone version.](Pictures/Proj8.png) 
If you wanted, you could plug your own phone into the computer and select your phone to download the app on your phone.
9. [After the application opens, log in with school id “1234567” and password “test”](Pictures/Proj9.png)
10. [Feel free to browse the app!](Pictures/Proj10.png)
The scanner portion of the app only works on an actual phone where the iPhone camera can be accessed.



And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Key Features

* Robust backend relational database to store information
* Well commented database access code
* Checkout with your phone for ease of access
* Intelligent keyword search algorithm to look for books
* Hold system that lets you reserve a book to pick up later
* Customized map to identify book locations
* Bug reporting to enable continuous development
* Smart resource management to reduce database calls and memory leaks

## Database Structure

Database is a relational MySQL database running the InnoDB engine. It uses various foreign key checks to ensure the integrity of the data and eliminate potential errors in database calls.
[You can see our design schema here](https://eric-cf.github.io/MAD-2018/) 

## Deployment

This application is supported by a server side script, so any user just has to connect with their account (made with the library when they join the school)

## Built With

* MySQL server hosted with bluehost.com
* PHP access code hosted with bluehost.com
* Swift code for UI and implementation
* CocoaPods for library dependency management

## Authors

* **Eric Cheng** - *Database and Backend* - [Eric-Cf](https://github.com/Eric-Cf)
* **David McAllister** - *UI design and Implementation* - [mcallisterdavid](https://github.com/mcallisterdavid)
* **Lily Li** - *Login and Code Deployment* - [lilyli333](https://github.com/lilyli333)

## License

This project is licensed under the GNU Lesser General Public License v3.0 - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Thanks to Stanford Mobile App Development course for posting learning resources
* Thanks to Mr. Kuramoto, the San Mateo Library branch manager, for answering our questions about library operations
* Thanks to Mr. Shelby, former computer engineer, for giving us feedback on user testing
* Special thanks to Mrs. Amity Bateman for answering our questions on what features Homestead High school wanted the most for a school library app

