# Session7Assignment1

5. Problem Statement

a. What is the use of SQlite open helper class in SQLite?
 SQLiteOpenHelper is used for executing SQL requests and managing a local database.
 
 SQlite open helper class in SQlite is used  to manage database creation and version management.
 Subclass are onCreate(SQLiteDatabase), onUpgrade(SQLiteDatabase, int, int) and optionally onOpen(SQLiteDatabase). 
 This class will takes care of opening the database if it exists, 
 creating it if it does not, and upgrading it as necessary.
 Transactions are used to make sure the database is always in a sensible state.
 
 

b. What is the use of OnUpgrade function in SQLiteOpenHelper class?

void onUpgrade (SQLiteDatabase db, int oldVersion, int newVersion)

OnUpgrade function in SQliteOpenHelper class  is used to update/ upgrade  the database structure.
The implementation should use this method to drop tables, add tables, or 
do anything else it needs to upgrade to the new schema version.


c. How to show sqlite database table information in android application 
what is the best way to do it?

To see the Database tables stored in SQLite Database. 
First you need the Database file which usually has the .db extension,
which can be searched using the Android Monitor's file explorer utility provided by the Android Studio.
(/data/data/com.yourpackge.name/databases/" to see what the database filename.Pull the database files to your desktop)
After you find the required SQLite Database file which is usually stored in application package's data/ folder,
has to be opened using another applicaiton called SQLite Broswer, 
Lightweight application to open and view database tables, schema and run SQL queries. 



