Steps:
1. Run git clone
2. Setup venv using python -m venv venv
3. Setup .env in config/settings/env
4. Configure database user if not already setup.
   create user 'user'@'host' identified by 'password';
   grant alter, create, select, insert, update, delete, references, index on schema_name.* to 'user'@'host';
   flush privileges;
