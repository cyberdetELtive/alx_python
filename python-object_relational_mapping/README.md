Project Description

This project involves working with a MySQL database and Python scripts to perform various tasks related to states and cities within the USA. The database is named hbtn_0e_0_usa, and the scripts use the MySQLdb module for database interaction.

Project Structure
0-select_states.py: This script lists all states from the hbtn_0e_0_usa database. It takes three arguments: MySQL username, MySQL password, and the database name. It connects to a MySQL server running on localhost at port 3306 and displays the results in ascending order by states.id.

1-filter_states.py: This script lists all states with names starting with 'N' (uppercase 'N') from the hbtn_0e_0_usa database. It takes the same three arguments as the previous script, connects to the MySQL server, and displays the filtered results.

2-my_filter_states.py: This script takes an argument (state name) and displays all values in the states table of hbtn_0e_0_usa where the name matches the argument. It also uses the MySQLdb module and avoids SQL injection.

3-my_safe_filter_states.py: Similar to the previous script, this one also filters states by name but is designed to be safe from SQL injection.

4-cities_by_state.py: This script lists all cities from the hbtn_0e_4_usa database. It takes three arguments: MySQL username, MySQL password, and the database name. It connects to a MySQL server running on localhost at port 3306 and displays the results in ascending order by cities.id.

5-filter_cities.py: This script takes the name of a state as an argument and lists all cities of that state from the hbtn_0e_4_usa database. It also takes MySQL username, MySQL password, and the database name as arguments. It avoids SQL injection and displays the results in ascending order by cities.id.

6-model_state.py: This script defines a class State and an instance Base using SQLAlchemy. The State class represents a state in the database with attributes id and name.

7-model_state_fetch_all.py: This script lists all State objects from the hbtn_0e_6_usa database using SQLAlchemy. It connects to a MySQL server, fetches the results, and displays them.

8-model_state_fetch_first.py: This script prints the first State object from the hbtn_0e_6_usa database. If the table is empty, it prints "Nothing." It uses SQLAlchemy to achieve this.

9-model_state_filter_a.py: This script lists all State objects from the hbtn_0e_6_usa database that contain the letter 'a' in their names. It uses SQLAlchemy for database interaction.