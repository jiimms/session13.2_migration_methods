Migration methods

To generate a new migration
rails generate migration MyNewMigration

To generate migrations that add fields to a table.
rails generate migration add_fieldname_to_tablename fieldname:string

To generate a migration to remove a column from the command line:
rails generate migration RemovePartNumberFromProducts part_number:string

To Change a column type
rails g migration ChangeBodyTypeInPosts