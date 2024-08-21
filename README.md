# Budget & Savings Tool

## Overview

The **Budget & Savings Tool** is a responsive web application designed to help you efficiently manage your income by allocating it into various categories and tracking your savings progress toward a specific goal. With its user-friendly interface, modern design, and built-in dark mode, this tool offers a pleasant experience whether you're on a desktop or mobile device.

## Features

- **Income Allocation**: Automatically divides your income into three key categories:
  - **Total Weekly Spending**: 75% of your income is allocated for daily expenses.
  - **Emergency Savings**: 10% of your income is set aside for emergencies.
  - **Investments**: 15% of your income goes toward investments.
  - **Savings for Goal**: Displays how much of your income should be allocated weekly to achieve your savings goal, if set.
  
- **Savings Goal Tracking**: Set a specific savings goal and a timeframe. The tool calculates whether you're on track to reach your goal, providing insights such as:
  - How many weeks you need to save to reach your goal.
  - Whether you are ahead or behind schedule.
  - Visual progress bar with color-coded feedback.
  
- **Dark Mode**: Easily switch between light and dark modes for a comfortable viewing experience in any environment.

- **Responsive Design**: The tool is optimized to work seamlessly across all devices, including desktops, tablets, and smartphones.

## How to Use

1. **Enter Your Pay Amount**: Input your total income in the designated field.
2. **Select Pay Frequency**: Choose your pay frequency (weekly, bi-weekly, or monthly) from the dropdown.
3. **(Optional) Set a Savings Goal**: If you have a specific savings goal, check the "Set a Savings Goal" box, then enter the goal amount and timeframe in months.
4. **Calculate**: Click the "Calculate" button or press the "Enter" key to view your income allocation and savings progress.
5. **View Results**: The tool will display your total spending, savings for the goal (if set), emergency savings, investments, and a visual progress bar if you have set a goal.
6. **Toggle Dark Mode**: Use the checkbox in the top-right corner to switch between light and dark modes.

## Technical Details

- **Technologies Used**:
  - HTML5
  - CSS3 (including CSS Variables for dark mode)
  - JavaScript (for calculations, dynamic content updates, and visualization)
  - Chart.js (for creating visual income allocation charts)

- **Responsive Design**: The layout is fully responsive, ensuring it adapts to various screen sizes for an optimal user experience.

- **Customizable**: You can easily adjust the income allocation percentages or add additional features by modifying the JavaScript logic.

## Installation

To use this tool:

1. Clone or download the repository to your local machine.
2. Open the `index.html` file in your preferred web browser.

```bash
git clone https://github.com/yourusername/budget-savings-tool.git
cd budget-savings-tool
