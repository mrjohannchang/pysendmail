# pysendmail

A simple command line tool for sending emails.

## Usage

```
$ pysendmail -h
usage: pysendmail [-h] [-f FROM_ADDR] -r RECIPIENTS [RECIPIENTS ...] -j
                  SUBJECT [-a ATTACHMENTS [ATTACHMENTS ...]]
                  [--smtp-host MAIL_SERVER] [--port PORT] [--ssl]
                  [--username USERNAME] [--password PASSWORD]

Quickly send an email. Mail contents would be read from standard input and it
could be empty.

optional arguments:
  -h, --help            show this help message and exit
  -f FROM_ADDR, --from FROM_ADDR
                        address the recipients see where the mail is from
  -r RECIPIENTS [RECIPIENTS ...], --recipients RECIPIENTS [RECIPIENTS ...]
                        recipients' email
  -j SUBJECT, --subject SUBJECT
                        mail subject
  -a ATTACHMENTS [ATTACHMENTS ...], --attachments ATTACHMENTS [ATTACHMENTS ...]
                        files to attach
  --smtp-host MAIL_SERVER
                        server address for SMTP service
  --port PORT           port on the smtp server
  --ssl                 using SSL or not
  --username USERNAME   username
  --password PASSWORD   password
```
