# Sqlalchemy-Migrate

## Setup Database

{{{
    migrate manage manage.py --repository=<repository> --url=<database connection string>
}}} 

## Initialise Database

{{{
    python manage.py version_control
}}}

## Create Migration

{{{
    python manage.py script "<Description>"
}}}

## Upgrade Database

{{{
    python manage.py upgrade
}}}

## Downgrade Database

{{{
    python manage.py downgrade
}}}
