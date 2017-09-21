# Links database examples setup

The script `dbsetup` creates and populates the databases required to
run the Links database examples. The script assumes that the postgres
role `links` already exists, and moreover, it assumes that the
authentication method is trust for this role on localhost.
