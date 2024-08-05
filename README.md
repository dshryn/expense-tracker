# Expense Tracker App with Flutter

This Flutter application is created to assist users in managing their finances by keeping track of and organizing their expenses. The app features a user-friendly interface that allows for easy addition, viewing, and deletion of expenses, as well as graphical representations of spending trends.

## Features

- **Expense Management**: Easily add, view, and delete expenses.
- **Categories**: Organize expenses into Food, Travel, Leisure, and Work.
- **Interactive UI**: Utilizes Theming, State Management and Custom Widgets for an engaging user experience.
- **Preserved native iOS and Android interfaces**: Displays platform-native styles for components like Alert-DialogueBoxes.
- **Chart Visualization**: Visualize your expenses to understand your spending habits better.

## App Structure

### Sections

- **Main Screen**: Displays a list of expenses and a summary chart.
- **Modal Overlay**: Form for adding new expenses.

### Flutter Concepts Used

- **State Management**: Uses native Flutter implementation with StatefulWidget and setState.
- **Navigation**: Implements modal bottom sheets for input forms.
- **Custom Widgets**: Encapsulates UI components like expense items and charts.
- **Theming and Styling**: Uses ThemeData contexts, LinearGradient, and other styling techniques.
- **Asset Management**: Efficiently manages icons and other assets with careful attention to related Element Tree.
  

## Setup and Installation

### Prerequisites

- [Flutter SDK](https://flutter.dev/docs/get-started/install) installed on your machine.
- An editor like [Android Studio](https://developer.android.com/studio) or [Visual Studio Code](https://code.visualstudio.com/).

### Steps

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/dshryn/expense-tracker.git
    cd expense-tracker
    ```

2. **Install Dependencies**:
    ```bash
    flutter pub get
    ```

3. **Run the App**:
    ```bash
    flutter run
    ```

## Usage

1. Launch the app on your device or emulator.
2. Press the "+" button to add a new expense.
3. Fill in the expense details (title, amount, date, and category).
4. View the list of expenses and the corresponding chart.
5. Swipe left or right on an expense to delete it, with an option to undo.

## File Structure

- **main.dart**: Entry point of the application.
- **models/expense.dart**: Defines the Expense model and categories.
- **widgets/expenses_list/expenses_list.dart**: Displays the list of expenses.
- **widgets/expenses_list/expense_item.dart**: Individual expense item widget.
- **widgets/chart/chart.dart**: Displays the chart summarizing expenses.
- **widgets/chart/chart_bar.dart**: Represents individual bars in the chart.
- **widgets/new_expense.dart**: Overlay form for adding new expenses.



