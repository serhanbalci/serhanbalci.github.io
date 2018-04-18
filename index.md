## Serhan Balcı

14 years of professional experience & knowledge about software development such as internet & portal development, new technologies, social media development, e-commerce systems and managing software development team members. 

Using ASP.NET C#, Ruby programming languages for developing and managing enterprise level projects. Also have a great knowledge about MS SQL Server, PostgreSQL and No-SQL solutions such as MongoDB, Couchbase, CouchDB, Redis. Also knowledge about Memcached and Elastic Search. 

Core Abilities : OOP Knowledge, Server Architecture, Managing Software Teams, Team Foundation Server 2010 / 2012, SQL and NO-SQL Solutions, Basecamp, Jira, MS Project, Github, Ubuntu, Nginx, Apache and Phusion Passenger.

### Apache2 Basic Authentication

```markdown
#sites-available altında oluşturduğumuz conf 
#dosyasının içerisine aşağıda ki kod bloğunu ekliyoruz. 

<Directory "/var/www/html/protected">
  AuthType Basic
  AuthName "Authentication Required"
  AuthUserFile "/etc/htpasswd/.htpasswd"
  Require valid-user

  Order allow,deny
  Allow from all
</Directory>

#daha sonra yeni bir htpasswd kullanıcısı oluşturuyoruz. 

htpasswd /etc/htpasswd/.htpasswd admin

```

### LoremPixel ile Dummy Resim

```markdown
http://lorempixel.com/400/200/sports/
```
