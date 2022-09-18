# Demo Flask

## Dependencies
You may need to install [sqlcipher](https://www.zetetic.net/sqlcipher/open-source/).

To install required dependencies you need to use `pip3 install -r requirements.txt` on project directory.

## Initializate DB
You need to add the Microsoft account that sends the emails in the script `schema.sql` replacing in `INSERT INTO credentials (name,user,password) VALUES ('EMAIL_APP','developmentcapstone', '$TR41NC0URS3R4$');`:
- `developmentcapstone` for the email. 
- `$TR41NC0URS3R4$` for the password.

After that, you need to run `flask init-db` on project directory.

## Run application
For run the app you need to use `flask run` on project directory.
