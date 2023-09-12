<!-- loio59515e5551304388bb721a2b7fdadad8 -->

# Modularizing Supported Templates

Templates are modularized to ease the creation of additional flow steps.



For certain templates, if depicted in the template's description, the following few additional features are available:

-   A template is modularized to ease the creation of additional flow steps to the integration flow:

    -   A Local Integration Process pool is available to contain the mapping files from the source ICO. With such a design, readability of the mapping steps is better and becomes convenient to add more mapping steps or maintain the sequence of message mappings and XSLT mappings.

    -   An Exception Subprocess pool is available for you to set up your own exception handling.


-   A Content Modifier step is added with headers *SAP\_Sender*, *SAP\_Receiver*, and *SAP\_MessageType*. The headers help you search for your messages in the monitoring of message processing.

    -   *SAP\_Sender* and *SAP\_Receiver* are mapped to the sender and receiver adapter types respectively.

    -   You can manually define the source value for the header *SAP\_MessageType*.


