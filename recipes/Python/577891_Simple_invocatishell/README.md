## Simple invocation of shell commandsOriginally published: 2011-10-04 23:50:17 
Last updated: 2011-10-21 06:44:35 
Author: Nick Coghlan 
 
Some simple wrappers around the subprocess functions for use in system administration utilities that frequently need to interpolate trusted data into shell commands (e.g. filenames from directory listings, etc):