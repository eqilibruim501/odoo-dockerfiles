Odoo 12.0
========

This docker image is for Odoo 12.0

After the download process is completed you can run the container with:

    docker run --restart=always -p 32769:8069 -p 32770:8072  -p 32771:22 -p 32772:5432 --name odoo12 -d IMAGE-ID
