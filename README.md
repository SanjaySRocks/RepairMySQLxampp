# RepairMySQLxampp
A Script which will repair your corrupt mysql xampp


Put Script in xampp/mysql folder and run the script


What script does?
1. Rename the folder mysql/data to mysql/data_old (you can use any name)
2. Create a new folder mysql/data
3. Copy the content that resides in mysql/backup to the new mysql/data folder
4. Copy all your database folders that are in mysql/data_old to mysql/data (skipping the mysql, performance_schema, and phpmyadmin folders from data_old)
5. Finally copy the ibdata1 file from mysql/data_old and replace it inside mysql/data folder
6. Start MySQL from XAMPP control panel
