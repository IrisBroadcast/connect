IRIS Connect - the SIP server configuration
===========================================

This is a Kamailio example configuration for running with the IRIS CCM.
The file is based on the default Kamailio configuration file.

The notable changes are the way we store data about registrations and 
dialogs and send to the CCM using HTTPS. 

This configuration is based on a database with kamailio accounts.
In production, Radius authentication is used today, but we have
plans to switch to MySQL based authentication.

For more information about Kamailio, please 
visit https://www.kamailio.org
