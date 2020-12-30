# Welcome to HasalaTech!
## Description
**HasalaTech** is a website that allow its users to create wallets, manage bills, and track spendings, all in one website. This website was created by **KFUPM** students as a **SWE363** course project, so it's not meant to be used in real life *in its current state*.

This website was created using frameworks and libraries like: 
- **Bootstrap Studio** to create the structure of the website.
- **Google Firebase** to manage the database, authentication, and storage of pictures and related data.
- **jQuery** to make writing barebones JavaScript less painful.
- **Chart.js** to display charts and statics about the user's financial activities.
- and **Git & Github** to manage version control.

The project was initially worked on in October, when we created the basic structure using a pre-made template provided by Bootstrap Studio. Since then, the project has been in halt until December 9th, where the team rushed development to make do before the deadline, which was on December 11th.

**Expect a lot of malfunctioning, redundant, and messy code within this repository. If you wish to check the source code, Proceed with caution.**

## How to Use
You can enter the website through this link: [Home - HasalaTech](https://hasalatech-14b00.web.app/). After that, click on either the **Sign In** or the **Sign Up**, then click on either **Login with Google** or **Register with Google**. Using your preferred Google account, then after a while, you'll be redirected to the **Dashboard** page.

Please be noted that registering or logging in using the regular way is **not fully functional**, so it is not recommended to use it.

Once you're in the **Dashboard** page, you'll have a default wallet with where you can store your balance and track your spendings, ~~supposedly~~. You can add to your **balance** through the **balance card** at the top. The cards besides it are for **spendings**, where you can add spendings with their category, and **track your average daily spendings**.

The **charts** beneath it display the **spendings** in the **current month**, as well as the amount of spendings each category has. Atop of the category chart you can **add category** to the categories list that the wallet has.

At the bottom of the page, the cards for **tracking wallets** and **bills** are displayed. Wallets card allow you to **add**, **modify**, and **delete wallets**. Bills card allows you to **add**, **modify**, and **delete bills**. Bills added will **deduct** from the wallet's balance when the **due date** approaches.

The **Income** page provides you with the ability to add sources of income and manage them. Currently, income does not affect the wallet's balance as it is not yet implemented.

The **Profile** page allows the user to **change the name** displayed on the side bar, as well as change their **email address** and **profile picture**.

Lastly, you can **logout** from the website using the logout button, pretty obvious I think...

## Functionalities
The website in its current state features these features (*nice*):
- Sign in/up using Google account
- Add balance
- Add spendings
- Show average daily spendings
- Show spendings chart
- Add category
- Show category chart
- Display wallets list
- Display bills
- Change profile picture
- Change username
- Add income source and amount

Unfortunately, the website **does not** have these features:
- Add more wallets
- Modify/Delete wallets
- Add bills
- Modify/Delete wallets
- Modify/Delete income
- Accurate chart of spendings’ categories
- Generate Excel sheet report

## Future
Frankly, the code is in a sorry state. A natural result when the work is rushed, but it was a good experience nonetheless. This project is more likely to be left as is, but if the team wished to continue the project, it'd absolutely be with a brand new interface and code, using more advanced frameworks for frontend and backend. Don't expected this repository to be updated as I will keep on living my life doing my things. I hope you'd look forward to my *(or our?)* next projects.
