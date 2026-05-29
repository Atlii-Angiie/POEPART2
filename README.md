# POEPART2
CYBERBOT – Cybersecurity Awareness Chatbot (POE Part 2)
Overview

CYBERBOT is a WPF-based cybersecurity awareness chatbot developed in C#.
The chatbot helps users learn about important cybersecurity topics such as:

Password safety
Phishing attacks
Safe browsing
Viruses and malware
Public Wi-Fi safety
Software updates
General online protection tips

The application includes:

A graphical user interface (GUI)
Animated backgrounds
Voice greeting
Chat functionality
Interest memory recall
Search history functionality
Features
User Interface
Modern WPF graphical interface
Multiple screens/grids:
Welcome screen
Username screen
Chat screen
Animated background colors
Voice Greeting
Plays a welcome .wav audio when the application starts.
Cybersecurity Chatbot

The chatbot responds to cybersecurity-related questions.

Supported Topics
Passwords
Phishing
Viruses
Cybersecurity
Wi-Fi safety
Software updates
Memory Recall

The chatbot remembers user interests.

Example:

I am interested in cybersecurity and hacking

The chatbot stores this information and reminds the user later during conversation.

Search History

The chatbot stores previous questions asked by the user and allows them to:

View search history
Track previous conversations
Error Handling

The application checks for:

Empty usernames
Empty questions
Invalid input
Special character sanitization
Technologies Used
C#
WPF (Windows Presentation Foundation)
.NET Framework
XAML
File Handling
Collections (ArrayList, List, HashSet)
Animations
Project Structure
Main Classes
MainWindow.xaml

Contains the graphical user interface.

MainWindow.xaml.cs

Controls:

chatbot logic
animations
chat processing
event handling
respond.cs

Stores chatbot responses and ignored words.

voice_greeting.cs

Handles voice greeting audio playback.

user_name.cs

Handles username validation and submission.

How the Program Works
Step 1 – Launch Application

The application starts and:

displays the welcome screen
plays a voice greeting
starts background animation
Step 2 – Enter Username

The user enters their username.

Validation ensures:

the username is not empty
Step 3 – Chatting

Users can ask cybersecurity questions.

Example:

What is phishing?

The chatbot searches for matching responses and replies appropriately.

Step 4 – Interest Storage

Users can tell the chatbot their interests.

Example:

I am interested in malware

The chatbot stores this information in:

interested_topic.txt
Step 5 – Search History

The chatbot records previous searches and allows users to view them.

Files Used
welcome.wav

Voice greeting audio.

logo.jpg

Application logo.

interested_topic.txt

Stores user interests.

search_history.txt

Stores user search history.

Installation Instructions
Requirements
Visual Studio
.NET Framework
Windows OS
Steps
Open the project in Visual Studio
Build the solution
Run the application
Example Questions
What is cybersecurity?
Tell me about phishing
How do I create a strong password?
Why are software updates important?
Is public Wi-Fi safe?
Future Improvements

Possible future enhancements:

AI integration
Database support
Dark mode
User login system
More cybersecurity topics
Speech recognition
Real-time API integration
Author

Developed for:
Programming POE Part 2

By:
Atlegang Pedinyane

License

This project is for educational purposes only.
