## Electric Bill Calculator
This is a basic web application that calculates the electricity bill based on the number of units consumed. The user enters the units used, and the program applies slab-based billing rates to display the final amount.

### Features
* Input field for units consumed
* Slabwise billing calculation
* Automatic amount display
* Single page with built-in styling
* No frameworks or external libraries

### Billing Slabs
| Units range | Rate per unit |
| ----------- | ------------- |
| 0 to 100    | 5 ₹           |
| 101 to 200  | 7 ₹           |
| 201 to 300  | 9 ₹           |
| 301 to 500  | 10 ₹          |
| Above 500   | 12 ₹          |

### How it Works
The user enters the consumed units and clicks the **Check** button. Based on the value, JavaScript calculates the total charge by applying the respective rate slabs.

### Technologies Used
* HTML
* CSS
* JavaScript

### How to Run
1. Download or clone this repository
2. Open the file `index.html` in any browser
3. Enter units and calculate bill amount

### Sample Screenshot
<img width="907" height="722" alt="image" src="https://github.com/user-attachments/assets/1af6736b-ccf6-4711-98b8-9a78afd219f0" />

### Future Enhancements
* GST and additional fixed-charge calculations
* PDF bill generation
* Responsive UI improvements
* Dark mode theme
