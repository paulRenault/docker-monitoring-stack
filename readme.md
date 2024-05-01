# Mailhog

On mac with apple silicon, mailhog does not work.
You need to build your hown image:

```bash
git clone https://github.com/mailhog/MailHog.git
cd MailHog
docker build -t mailhog .
```