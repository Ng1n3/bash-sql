# create a database from a csv file using bash scripting

## restore the database using pg_dump
pg_dump --clean --create --inserts --username=freecodecamp students > students.sql