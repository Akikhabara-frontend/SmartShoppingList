Smart Shopping List 
1. Problem Definition & Project Requirements 
Problem Statement 
Many people struggle with shopping in an organized and budget-friendly way. 
Paper lists or simple notes apps do not help users track how much money they 
spend, which categories cost the most, or how close they are to their budget 
limit. Because of this, people often overspend, forget items, or lose control of 
their expenses, which makes shopping stressful and inefficient. 
Project Objectives 
The main goal of this project is to create a mobile application that helps users 
shop smarter and stay within their budget. The application aims to: 
● Make shopping lists easy to create and manage 
● Track expenses in real time while shopping 
● Visually show budget usage and progress 
● Provide simple statistics about spending habits 
● Offer a clean and easy-to-use interface 
● Allow future expansion with more advanced features 
Project Scope 
The Smart Shopping List application includes: 
● Creating and managing multiple shopping lists 
● Adding items with prices and categories 
● Automatic budget calculation and warnings 
● Basic analytics and statistics 
● Support for both Android and iOS platforms 
Target Audience 
This application is designed for: 
● Students with limited budgets 
● Families managing household expenses 
● Budget-conscious users 
● Anyone who wants a more organized shopping experience 
2. System Design & Architecture 
Technology Stack 
● Framework: Flutter 3.0+ (Dart) 
● State Management: Provider (v6.0.5) 
● UI Design: Material Design 3 with Cupertino support 
● Libraries Used: 
○ flutter_slidable for interactive list actions 
○ intl for future localization support 
○ flutter_lints to maintain clean and readable code 
● Development Tools: VS Code / Android Studio with Flutter SDK 
3. Functionality & Implementation 
Shopping List Management 
Users can create and delete unlimited shopping lists. Each list has its own name 
and budget. Lists are displayed as cards showing how many items are bought, 
how much money is spent, and how close the user is to the budget limit. All 
updates appear instantly in the app. 
Item Management 
Users can add items by entering the item name, quantity, price, and category. 
The app validates all inputs to prevent errors. Items can be marked as 
purchased, edited, or deleted. The total price of items is calculated live before 
saving. 
Budget Management 
Each list has its own budget. The app automatically calculates how much money 
is spent and how much remains. A color-coded progress bar shows the budget 
status: 
● Green – safe spending 
● Yellow – close to the limit 
● Red – budget exceeded 
Analytics & Statistics 
The statistics screen provides: 
● Total amount spent 
● Average purchase cost 
● Number of purchases 
● Spending distribution by category 
● Progress comparison between lists 
User Experience Features 
● Friendly messages when lists or items are empty 
● Clear validation messages in forms 
● Responsive design for different screen sizes 
4.Screens
<img width="759" height="357" alt="image" src="https://github.com/user-attachments/assets/c19d71b7-7420-4371-80de-80b804808cbe" />

Screen 1: Main Shopping Lists Screen 
Displays all shopping lists in card format with clear progress indicators. Each 
card shows list name, item count (purchased/total), budget status 
(spent/remaining), and a color-coded progress bar. A prominent floating "+ New 
List" button enables quick list creation. Bottom navigation provides access to 
Statistics and Settings sections.
<img width="761" height="359" alt="image" src="https://github.com/user-attachments/assets/9ec97cd8-ce11-4702-93b5-67a824b30ac4" />

Screen 2: Statistics Dashboard 
Comprehensive analytics screen showing total spending (180₸), average 
purchase amount, and purchase count. Features categorized expense breakdown 
(Groceries, Dairy) and active list progress indicators (4%, 0%). Visual card 
layout organizes data into digestible sections with icons and progress bars for 
quick insights. 
<img width="762" height="359" alt="image" src="https://github.com/user-attachments/assets/23cecd2d-8e7c-411f-a2ce-0e365ca4003f" />

Screen 3: Settings Screen 
Simple list interface with six non-functional placeholder options: App Theme, 
Notifications, Language, Clear Data, About App, and Rate App. Serves as a 
foundation for future configuration features with clean typography and 
iconography, though currently implemented as a static UI prototype. 
<img width="759" height="697" alt="image" src="https://github.com/user-attachments/assets/9987cf7d-d460-4824-8bed-9c9663d64b14" />

Screen 4: List Detail View 
Shows detailed breakdown of "Weekly Groceries" with budget summary (180₸ 
spent, 5000₸ budget, 4820₸ remaining). Lists all items with quantity, price, and 
category per item. Includes an "Add Item" button for expanding the list. 
Provides individual item tracking within a specific shopping list.
