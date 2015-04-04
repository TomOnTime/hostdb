HostDB is a system for generating internal DNS zones, external DNS zones, and DHCP configuration data from the same hostlist.txt file. Keep your configurations consistent by generating them all from the same source.

The files that are generated are beautifully formatted and easy to "diff" before they are put into production. It even generates the Makefile required to make the system all work together. A "file push" mechanism (mkdestinations), plus many DNS-related utilities are included (sortbyip, genrange, comparezones, checkrootcache).

First unveiled at the Usenix LISA 2005 Conference, San Diego, December 4-9, 2005 under the title, "HostDB: The Best Damn host2DNS/DHCP Script Ever Written".  Released under the GPL on January 8, 2005.

The software is appropriate for sites that are small enough that they keep their list of hosts in a text file, not a database.  Everyone is encouraged to join the project!  Most of the recent code enhancements have been from external contributors!