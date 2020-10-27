# Nagios `check_krb5` Kerberos Plugin

	Usage: check_krb5 -H<host> -r <realm> -p <principal> -k <keytab_file> [-p <port>]

	-H, --hostname=HOST
			Name or IP address of host to check
	-r, --realm=NAME
			Kerberos realm to authenticate to
	-p, --principal=NAME
			Name of principal to try authentication as
	-k, --keytab=file
			Path to keytab file containing key to principal
	-P, --port=INTEGER
			Port the kdc runs on
	-v, --verbose
			Print extra debugging information

Original homepage: http://www.spock.org/check_krb5.html
