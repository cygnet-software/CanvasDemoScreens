Comm. Stats Screens

These screens are designed to highlight possible issues with your comm. and remote devices.

They should integrate into your system without having to make changes to the screen configuration. They are
designed to be loaded from the BSS. If you want to run them locally, you'll need to change the source of the
scripted hyperlinks and objects to Local.

The screens reference a collection of system UDCs that our EIE team picked as some of the most useful when
attempting to diagnose or identify issues with communications. If you do not have these UDCs defined in your
system, some of the controls will be blank. You can change the UDCs easily by changing the properties of the 
combo boxes driving the heat and tree maps.

NOTE:

To find the Remote Devices associated with a selected Comm. Device, these screens use our ODBC driver, so 
you will need to have that installed. You will also see script that checks via the COM API, but this is very 
inefficient and will not perform well. It is included to support the case when installing the ODBC driver is 
not possible.

Requires Canvas 9.2.1005
