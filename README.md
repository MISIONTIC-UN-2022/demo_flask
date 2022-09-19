# Demo Flask

## Dependencies
You may need to install [sqlcipher](https://www.zetetic.net/sqlcipher/open-source/).

To install required dependencies you need to use `pip3 install -r requirements.txt` on the project directory.

## Initializate DB
To run the app, you need to provide a Microsoft account for the app to send/receive emails. To add this account follow these steps:

1. Open the file `schema.sql`.
2. Locate the line `INSERT INTO credentials (name,user,password) VALUES ('EMAIL_APP','developmentcapstone', '$TR41NC0URS3R4$')`.
3. Replace `developmentcapstone` with the email address.
4. Replace `$TR41NC0URS3R4$` with a password to access the email account.
5. Run `flask init-db` on the project directory.

## Run application
For run the app you need to use `flask run` on the project directory.
