# Smart VAT Deductor (Alt + V)
A lightweight AutoHotkey utility designed for instant tax calculations. This script automates the process of converting Gross amounts to Net (Less VAT) directly within any text field or application.
## 🛠 Functionality
The script performs a Gross to Net conversion using the standard Philippine VAT rate:

### Key Features: Auto-Cleaning: Automatically strips commas (,) and extra spaces from your selection so you don't have to manually edit the number. Accounting Standard: Formats the output to exactly 2 decimal places (e.g., 1500 becomes 1339.29). Instant Replacement: Overwrites the highlighted text with the calculated result in one keystroke. ## ⌨️ How to Use Highlight any number containing VAT (e.g., 1,120.00). Press Alt + V. The number is instantly replaced by the Net amount (e.g., 1000.00). ## 🔧 Technical Logic Trigger: !v (Alt + V) Input Handling: Uses ClipWait to ensure the clipboard is ready before calculation. Data Sanitation: Utilizes StrReplace to handle formatted numbers with thousands separators. Formatting: Uses Format("{:.2f}") for professional financial precision. > Developer: Jerom Requillo
> Purpose: Workflow Efficiency & Financial Automation
>
