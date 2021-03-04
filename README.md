# shop-inventory

# create database
Enter commands into terminal to initialize the database:
1. Creates an empty database.
2. Populates the tables with data.
``
createdb shopinventory
psql -f schema.sql shopinventory && psql -f seed.sql shopinventory
``
