# Gnuteca3.8
Path traversal present in Gnuteca v.3.8
SQL Injection present in Gnuteca v.3.8

------------------------------------------

[Additional Information]
Unauthenticated users can exploit:
  - Path Traversal in GNUTeca v.3.8. The parameter "file", located at "file.php?folder=/&file=" is vulnerable to Path Traversal attacks.

  - SQL Injection in GNUTeca v.3.8. The parameter “exemplaryStatusId”, located at “/index.php?module=gnuteca3&action=main:search:simpleSearch" is vulnerable to SQL Injection attacks.

------------------------------------------

[VulnerabilityType Other]
Path Traversal

SQL Injection
------------------------------------------

[Vendor of Product]
Solis

------------------------------------------

[Affected Product Code Base]
GNUTeca v.3.8

------------------------------------------

[Reference]
https://www.solis.com.br/gnuteca

------------------------------------------
[Researcher]
Bruno de Barros Bulle

https://www.xlabs.com.br

https://www.linkedin.com/in/bruno-de-barros-bullé-7237a129/
