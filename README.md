# jss_group_mysql_query
MySQL queries wrapped in bash scripts to deliver all appearances of LDAP groups or JSS groups in various scopes

If you've ever wanted to make changes to a JSS mobile device group, computer group, user group, or an LDAP group, but you wanted to know what eBook scopes, Mac/iOS app scopes, Mac/iOS configuration profile scopes, policy scopes, or restricted software scopes your JSS group or LDAP group might be apart of before you make those changes, break things, and have a really bad day, these scripts might help you. (Because let's be honest, who still uses managed preferences or vpp assignments??)

They're extremely fast when compared to using the JSS API in bash scripts for the same purpose, and return the results to the terminal in easy to read SQL table views.

Just change your database name and database password (change the user if you're not using the mysql root user), and run the scripts.
