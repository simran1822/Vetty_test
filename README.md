# Vetty_test
Designed and implemented SQL Server logic to showcase  technical skills and problem-solving abilities

This code focuses on analyzing buyer transaction patterns using SQL Server. A transactional dataset containing purchase timestamps, refund events, and store-item details was processed to identify customer behavior trends. Using Common Table Expressions (CTEs) and the ROW_NUMBER() window function, each buyer’s purchases were ranked chronologically while excluding refunded transactions to maintain data integrity.

The core objective was to retrieve only the second purchase per buyer (ignoring any refunded transactions), which helps in understanding repeat purchase tendencies and customer lifecycle stages. The solution demonstrates proficiency in writing optimized SQL queries, leveraging window functions, date filtering, and building analytic logic inside SQL Server Management Studio (SSMS). The final output correctly identifies that only buyer_id = 3 has a valid second purchase in the dataset.
