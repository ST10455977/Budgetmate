# Budgetmate


A robust, feature-rich Android application designed to help users take control of their personal finances. With tracking tools, budget goal setting, visual analytics, and built-in gamified achievements, BudgetApp transforms how you monitor expenses, save money, and achieve financial literacy.

 Features

1. Secure Authentication
* **User Registration & Login:** Secure account creation (`activity_register.xml`, `activity_login.xml`) to keep your financial data private and secure.
* **Session Management:** Persistent login sessions to quickly access your dashboard without entering credentials every time.

 2. Comprehensive Financial Dashboard
* **Centralized Hub:** View your net balance, recent transactions, and active saving goals at a glance from the primary dashboard (`activity_dashboard.xml`, `activity_main.xml`).
* **Quick Actions:** Instantly add standard income/expenses or update budget goals right from the home screen.

3. Transaction Management
* **Log Income & Expenses:** Easily input transactions with detailed parameters including amount, category, date, and description (`activity_add_transaction.xml`).
* **Transaction History:** Search, filter, and review historical logs in a clean, scrollable list interface (`activity_transactions.xml`, `item_transaction.xml`).

4. Smart Budgeting & Goal Tracking
* **Set Savings Goals:** Define specific financial targets (e.g., emergency fund, vacation, new tech) with targeted deadlines (`activity_add_goal.xml`, `activity_goals.xml`).
* **Budget Thresholds:** Create monthly or weekly category limits to proactively prevent overspending (`activity_budget_goals.xml`, `item_goal.xml`).
* **Progress Indicators:** Visual tracking meters showing how close you are to reaching your goals or exceeding your budget.

5. Visual Analytics & Insights
* **Spending Graphs:** Dynamic data visualization utilizing graphical charts to reveal where your money goes (`activity_spending_graph.xml`).
* **Category Breakdowns:** See exact percentages of your monthly expenditure allocated to food, rent, entertainment, utilities, and more.

6. Gamified Achievements System
* **Financial Milestones:** Earn unique badges and level up your financial health as you build healthy habits (`activity_achievements.xml`).
* **Positive Reinforcement:** Unlock achievements for actions like "7-Day Expense Logging Streak", "Saved Your First $100", or "Stayed Under Budget for a Month".

---

 Architecture & Tech Stack

* **Platform:** Android
* **UI Architecture:** XML Layouts powered by modern **Material Design 3 (M3)** components for beautiful themes, tactile touch targets, and a premium aesthetic.
* **Minimum SDK Support:** Android 5.0+ (API Level 21) using modern Backports and AppCompat layers.
* **Key Libraries Integrated:**
    * `androidx.appcompat` & `androidx.activity` (Modern backward compatibility)
    * `com.google.android.material` (Material Design components, chips, dialogs, and time-pickers)
    * `androidx.cardview` (Elevated card elements for clear content separation)



 Project Structure (Layout Highlights)

The app's user interface is logically modularized across distinct activity layers:
* `activity_main.xml` / `activity_dashboard.xml`: Core application landings and summary interfaces.
* `activity_transactions.xml` & `activity_add_transaction.xml`: Components managing ledger input and visualization.
* `activity_goals.xml` & `activity_budget_goals.xml`: Form structures and dynamic listings for budget rules and financial targets.
* `activity_spending_graph.xml`: Specialized template for parsing and displaying visual charts.
* `activity_achievements.xml`: Beautiful milestone grid showcasing user awards.



  Building and Installation

 Prerequisites
* Android Studio Jellyfish / Koala (or newer)
* Android SDK 34+
* JDK 17

 Steps to Run from Source
1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/yourusername/BudgetApp.git
    cd BudgetApp
    ```
2.  **Open in Android Studio:**
    * Launch Android Studio, select **Open**, and navigate to the root directory of the cloned project.
3.  **Sync Project with Gradle:**
    * Allow Android Studio to download the necessary dependencies and finish the indexing process.
4.  **Run the App:**
    * Connect an Android device with USB Debugging enabled, or set up an Android Virtual Device (AVD).
    * Click the **Run** button (`Shift + F10`) in the toolbar to compile and install the application.


Security & Privacy

* **Local/Remote Data Isolation:** User login states are securely compartmentalized.
* **Input Validation:** Strict UI form validation on transaction entry prevents empty fields, invalid decimal structures, or negative values from corrupting your financial records.


https://drive.google.com/file/d/1o7FMLk9k3xnNBsr0RZkkQv58S5K0aipu/view?usp=drive_link

https://github.com/ST10455977

README.md





