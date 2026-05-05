# snowpark-basic-deployment

snow --info

# add connections -  "value": "/home/codespace/.config/snowflake/config.toml"

snow connection --help

snow connection test --help

snow connection test --connection trail

snow snowpark init --help

snow snowpark init nagesh_snowpark_deployment

cd nagesh_snowpark_deployment/

snow snowpark build

snow snowpark deploy --helpsnow snowpark deploy --connection trail