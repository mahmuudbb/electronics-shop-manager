# Electronics Shop Manager
Node.js + Express + MySQL app for an electronics/accessories shop.

Includes owner account setup, hashed passwords, server-enforced owner/manager/staff roles, product inventory, customers, sales invoices, stock reduction in a transaction, payments against balances, invoice printing, settings and CSV exports.

## Railway
1. Upload these files to your GitHub repository.
2. Create a Railway service from that repository and add a Railway MySQL database.
3. Make sure the app receives `MYSQLHOST`, `MYSQLPORT`, `MYSQLUSER`, `MYSQLPASSWORD`, and `MYSQLDATABASE` (or `MYSQL_URL`).
4. Set `SESSION_SECRET` to a long random secret and `NODE_ENV=production`.
5. Deploy and generate a public domain. Open it and create the first owner account.

Do not commit `.env` or secrets. Test with sample data before real business use. The default session store is in memory; configure persistent sessions and a tested backup policy for production.
