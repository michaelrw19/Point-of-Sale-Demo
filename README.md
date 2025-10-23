# Point-of-Sale-Demo
This is a repo to showcase my point-of-sale program to help a retail store transition from a traditional handwritten receipt to a digital receipt. More features will be added soon. <br>
Demo Video: https://drive.google.com/drive/folders/1G_0xHELZfxQDa4qtKuuetJjGTIUMas43?usp=sharing <b>(Outdated)</b>

Frontend: HTML, CSS, Boostrap, JavaScript, and Vue.js. <br>
Backend and Database: Python, Flask, SQLite

Note: For privacy reasons, all of the product, prices, address, and name are fake. They do not correlate to any real products.

# Instructions
Launch POS.exe under /dist and use the following accounts:
- Usernames: owner, admin, resupManager, clerk 
- Password: 0000 (same for all)
Each account has different privileges, owner has the highest authorization level.

# Features:
- Manage orders various order types and supply purchases.
- Summary of transactions and driver report.
- Manage products and price modification, customer list, drivers list, user list.
- User authentication and authorization (RBAC).
- Receipt printing (Requires ESC/POS printer named "POS-80C" in your computer system).
- Excel Download (appear in /Demo/dist/Excel Files).
- Auto sign out on 15 minutes of idle.
