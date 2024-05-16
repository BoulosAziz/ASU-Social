# Social-Media
Text based social media platform that allows creating users and logging in, as well as following other users and liking and commenting on other posts.

# ASU-Social

Welcome to ASU Social! This is a Java-based application that allows users to make text posts, like posts, comment on posts, add and remove friends, and update their profiles.

## Getting Started

### Prerequisites

To run this application, you need to have Java installed on your system. You can download and install Java from [(https://www.java.com/en/download/)].

### Installation

1. Download the zip file.
2. Run the src file on any compiler that supports Java. (IntelliJ, NetBeans, VS, etc)
 
## Usage

### Running the Application

1. Run the main Java class.

### Functionality


1. **Creating Users**: Users can create a new account with a First Name, Last Name, E-mail, and Password.
2. **Logging in**: Users can log in with accounts previously made and saved in the mySQL database.
3. **Making Text Posts**: Users can make text posts by entering their post content.
4. **Liking Posts**: Users can like posts made by other users.
5. **Disliking Posts**: Users can dislike posts they liked previously made by other users.
6. **Commenting on Posts**: Users can comment on posts made by other users.
7. **Adding Friends**: Users can add other users as friends.
8. **Removing Friends**: Users can remove friends from their friend list.
9. **Updating Profile**: Users can update their profile information such as name, change password, etc.

## Database

This project uses MySQL as its database management system. MySQL is an open-source relational database management system that is widely used for various applications.

### Setting up the Database

To set up the database for this project, follow these steps:

1. Install MySQL on your system if you haven't already. You can download MySQL from [(https://dev.mysql.com/downloads/)].
   
2. Create a new database for this project using the MySQL command line or a graphical interface like MySQL Workbench.

   ```sql
   CREATE DATABASE asu_social;

3.Create tables within the asu_social database for storing user information, posts, comments, likes, etc. You can find the SQL scripts to create these tables in the database_scripts directory.

4,Configure the database connection settings in the project's configuration file (config.properties or similar) to connect to your MySQL database.

## Contributing

Thank you for your interest in contributing to this project! Even though we don't have a GitHub repository set up for this project, there are still ways you can contribute:

1. **Feedback**: Provide feedback on the project. Let us know what you liked, what could be improved, or any ideas you have for new features.

2. **Spread the Word**: Help spread the word about the project. Share it with your friends, colleagues, or on social media.

3. **Documentation**: If you notice any missing or unclear documentation, feel free to suggest improvements or additions.

4. **Bug Reports**: If you encounter any bugs or issues while using the project, please let us know by emailing us at [boulos.wagdy@gmail.com].

5. **Feature Requests**: If you have ideas for new features or improvements, we'd love to hear them! Send us an email with your suggestions.

6. **Code Contributions**: While we don't have a public repository for this project, if you have code contributions or improvements you'd like to suggest, please email us at [boulos.wagdy@gmail.com]. We'll review your suggestions and integrate them into the project as appropriate.

We appreciate any contributions you can make to help improve this project and make it more useful for others!


## License

This project is licensed under the MIT License.

MIT License

Copyright (c) [2024] [ASU-Social]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Acknowledgments

Special thanks to Dr. Mahmoud Khalil & Eng. Mahmoud Soheil for inspiration and guidance.


