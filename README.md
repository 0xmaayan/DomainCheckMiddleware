# DomainCheckMidleware

Get the origin of the incoming request and check if this domain is allowed.
If not allowed, fire unauthorized event and throw an exception

* Add ALLOWED_DOMAINS to your .env file -
ALLOWED_DOMAINS=localhost,domain.com,domain2.co
