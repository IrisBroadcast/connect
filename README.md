IRIS Connect - the SIP server configuration
===========================================

This is a Kamailio example configuration for running with the IRIS CCM.
The file is based on the default Kamailio configuration file.

The notable changes are the way we handle data about registrations and 
dialogs (codec sessions) and send to the CCM server using HTTPS. 

This configuration is based on a database with kamailio accounts.
The Kamailio subscribe table is used, but you can change to the
CCM sipaccount table.

This configuration is verified with Kamailio versions 5.1 and 5.2.

For more information about Kamailio, please 
visit https://www.kamailio.org
