DEPLOYED:https://atheeruwu.github.io/centmaker/
1. **Input Validation**:  
   ```javascript
   if (!(Number.isFinite(+io.input)) || io.input.indexOf('-') != -1) io.output = `<p class="app__output">This is incorrect value</p>`;
   ```
   - Ensures the input is a valid positive number, preventing errors and providing user feedback.

2. **Dollar-to-Cent Conversion**:  
   ```javascript
   cents = Math.round(+io.input * 100);
   ```
   - Converts the dollar input into cents, essential for the coin breakdown calculation.

3. **Coin Breakdown Calculation**:  
   ```javascript
   quarter = Math.floor(number / 25); balance = number % 25;
   ```
   - Splits the total cents into quarters (similar lines exist for dimes, nickels, and pennies), which is the core functionality of the app.
  





![calculatorr](https://github.com/user-attachments/assets/c4c906c9-5fb0-41aa-b523-13050b87b5cf)

![calculator 1](https://github.com/user-attachments/assets/c0052fe8-bb9b-4981-9daa-06cc1ba725d6)






     
