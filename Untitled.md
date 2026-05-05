

MSSQL SERVER			MSACESS            ORACLE/MYSQL

using System.Data.Sqlclient       OleDb                   Orcl

usig System.Data

\--------------------------------------------------------------------------

SqlConnection			OleDbConnection        OrclConnection

SqlCommand			OleDbCommmand		OrclCommand

SqlDataReader

SqlDataAdapter





DataSet

DataRow

DataView

\---------------------------------------------------------------------------

Connection : In order to establish the connection between front

&#x09;    and backend we use this object

&#x09;

&#x09;    In order perform an query execution we need open the connection

&#x09;    to open the connection we use open()  non static method.

&#x09;    to close the connection we use Close() on non static method.



&#x09;    In order to change the data base we use connection object.



&#x09;    **This object can hold the information about the database name**

&#x09;    **and server name.**



Command : It is responsible to hold the query and execute the query

&#x20;         In order to hold the query we use string variable is

&#x09;  **CommandText**

&#x09;  This query can hold any query

&#x09;  In order to execute these

&#x09; Insert/Update/Delete queries we use non static of command class

&#x09; is **ExecuteNonQuery(),** The  return type this method is Integer

&#x09;If the query the executed successfully , it returns value >0

&#x20;        If the query is not executed returns 0



&#x09; In order to execute select query we use non static method

&#x09;**ExecuteReader()**

&#x09;

&#x09;	Ado.net we use Two Architectures

&#x09;	1.Connected Architecture

&#x09;	2.DisConnected Architecture



&#x09;		Steps



&#x09;	1.Create the Data base and Table.(Table\_employee)



&#x09;	2.Create the ConsoleApplication.(ConsoleApp5)



&#x09;	3.Employee class



&#x09;	4.BusinessLogic



&#x09;	5.Work with application in Program.



&#x09;	https://github.com/sssituser/ConsoleApp5.git

