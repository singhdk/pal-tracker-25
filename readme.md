flyway -url="jdbc:mysql://localhost:3306/tracker_dev" -locations=filesystem:databases/tracker clean migrate

flyway -url="jdbc:mysql://localhost:3306/tracker_test" -locations=filesystem:databases/tracker clean migrate