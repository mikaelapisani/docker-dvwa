# docker-dvwa
Docker image for DVWA([Damn Vulnerable Web Application](http://www.dvwa.co.uk/))

# Note
This container runs directly with an initialized MySQL database.
So, this ready for testing without any further manual setup step's.

# Login creds
username: admin
password: password

# Using

- Pull image `docker pull aracloud/docker-dvwa`
- Start with random mysql password: `docker run -dit -p 80:80 aracloud/docker-dvwa
- Or set environment variable: `docker run -d -p 80:80 -p 3306:3306 -e MYSQL_PASS="mypass" aracloud/docker-dvwa`
