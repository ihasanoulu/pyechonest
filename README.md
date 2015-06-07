sExyernal Libraries used are 

-sqlite3 time sys re os.
-One can look at the databse uisng firefox extension sqlite(https://addons.mozilla.org/en-US/firefox/addon/sqlite-manager/)
-The database can be setup by using python command(after naviagting to the root directory)

typing in the command prompt

python

db_path='db/sportshall.db'
import sportshall
db=sportshall.ForumDatabase()

Database can be set up by calling the method in the command prompt after typing above commands


create_sports_table()

We reccomend to populate databse using sqlite firefox extension.Or by calling methods  
-  adduser(username,password,dateofbirth,gender,email,student_id=None)
and
-  createSport(self,sport_id,sportname,hallnumber,time)
 in the python command prompt

Database can be tested using following fucntion in pyhton command propmpt
login(self, username, password):
delete_user(self,username):
getSport(self,sportName): getUserSport(self, username=None, number_of_sports=-1, before=-1, after=-1):
getUsers(self):
getUser(self,username):
contains_user(self, username):

