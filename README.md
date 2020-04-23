# TBDBT
CIDRI Africa Harmonised TB database REDCap template

## REDCap setup

To set up your own instance, REDCap has requires three main components:

1. Web server with PHP (PHP 5.3.0+, including support for PHP 7). Apache (any OS) or Microsoft IIS (Windows).
    - [Apache on Ubuntu](https://ubuntu.com/tutorials/install-and-configure-apache#1-overview)
    - [Apache on Windows](https://httpd.apache.org/docs/2.4/platform/windows.html)
2. MySQL database server (MySQL 5.0+, MariaDB 5.1+, or Percona Server 5.1+). A MySQL client (e.g., phpMyAdmin, MySQL Workbench) is required for performing installation/upgrades.
    - [MySQL setup](https://dev.mysql.com/doc/mysql-installation-excerpt/5.7/en/)
3. SMTP email server. Configure PHP with an institutional SMTP server or install an SMTP to use for sending emails out of REDCap.

https://projectredcap.org/software/requirements/


### Installing REDCap

Once the above requirements are met, installing REDCap can be done by:

1. Obtain a REDCap Licence [here](https://projectredcap.org/partners/join/)

2. Download the REDCap file

3. Place the redcap folder in the www directory (In the case of Apache)

For detailed instructions on how to setup a REDCap instance, please refer to the documentation produced by the H3Africa team [here](https://www.h3abionet.org/images/DataAndStandards/REDCap/Basic_Steps_and_Requirements_for_setting_up_REDCap.pdf)


## Using the CIDRI Africa Harmonised TB database REDCap template

Please refer to the instructions in the "Set-up guide 20200204.docx" file found in this repository for information on how to apply the template and set up a study.


