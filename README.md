# BillingApp

BillingApp is a mobile application developed to manage bills using RecyclerViews and Rooms Database. The app includes features for adding, editing, and deleting bills and provides a user-friendly interface for managing these tasks.

## Table of Contents
- [Project Structure](#project-structure)
- [Features](#features)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Structure
.
├── app
│   ├── src
│   │   ├── main
│   │   │   ├── java
│   │   │   │   └── com
│   │   │   │       └── example
│   │   │   │           └── billingapp
│   │   │   │               ├── MainActivity.java
│   │   │   │               ├── Bill.java
│   │   │   │               ├── BillAdapter.java
│   │   │   │               └── fragments
│   │   │   │                   ├── BillsFragment.java
│   │   │   │                   ├── CreateBillFragment.java
│   │   │   │                   ├── EditBillFragment.java
│   │   │   │                   ├── BillSummaryFragment.java
│   │   │   │                   ├── SelectCategoryFragment.java
│   │   │   │                   └── SelectDiscountFragment.java
│   │   │   ├── res
│   │   │   │   ├── layout
│   │   │   │   │   ├── activity_main.xml
│   │   │   │   │   ├── fragment_bills.xml
│   │   │   │   │   ├── fragment_create_bill.xml
│   │   │   │   │   ├── fragment_edit_bill.xml
│   │   │   │   │   ├── fragment_bill_summary.xml
│   │   │   │   │   ├── fragment_select_category.xml
│   │   │   │   │   └── fragment_select_discount.xml
│   │   │   ├── values
│   │   │       ├── strings.xml
│   │   │       └── styles.xml
└── build.gradle
└── README.md

## Features
	•	Welcome Activity: Displays a welcome screen with a “Start” button that navigates to the main activity.
	•	Bills Fragment: Shows a list of bills using RecyclerView, fetched from the Rooms Database.
	•	Create Bill Fragment: Allows users to add new bills with various attributes such as name, amount, discount, date, and category.
	•	Edit Bill Fragment: Enables users to edit existing bills.
	•	Bill Summary Fragment: Displays a summary of a selected bill.
	•	Select Category Fragment: Allows users to select a category for a bill.
	•	Select Discount Fragment: Allows users to select a discount for a bill.

## Setup Instructions
1. Clone the Repository
   git clone git@github.com:Senaye2003/BillingApp.git
   cd BillingApp
   
2.	Open the Project in Android Studio
	•	Open Android Studio and select Open an existing project.
	•	Navigate to the BillingApp directory and select it.

3.	Build the Project
	•	Click on Build in the top menu and select Make Project to build the project and download the necessary dependencies.

## Usage

	•	Welcome Activity: Displays when the app is launched. Click “Start” to navigate to the main activity.
	•	Bills Fragment: Displays a list of bills. Click “Clear” to delete all bills, “New” to create a new bill, “Trash Can” icon to delete a bill, and “Edit Icon” to edit a bill.
	•	Create Bill Fragment: Allows adding a new bill with details such as name, amount, discount, date, and category. Click “Submit” to save the bill.
	•	Edit Bill Fragment: Enables editing of an existing bill’s details. Click “Submit” to update the bill.
	•	Bill Summary Fragment: Shows the summary of a selected bill. Click “Delete” to remove the bill, or “Back” to return to the previous screen.
	•	Select Category Fragment: Allows selection of a bill category from a list.
	•	Select Discount Fragment: Allows selection of a discount value for a bill.
## Contributing
  Contributions are welcome! Please follow these steps to contribute:
	1.	Fork the repository.
	2.	Create a new branch (git checkout -b feature-branch).
	3.	Make your changes.
	4.	Commit your changes (git commit -m 'Add some feature').
	5.	Push to the branch (git push origin feature-branch).
	6.	Open a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for more information.
