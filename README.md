# postfix

Configure postfix clients

## Variables

* `smtp_hostname` - Mandatory
* `smtp_username` - optional
* `smtp_password` - optional

SASL authentication to the SMTP service will be configured only
if both `smtp_username` and `smtp_password` is set - otherwise
it will connect to SMTP anonymously.
