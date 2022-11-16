# Sample Database Dockerfile

This is a play repo for S1 Informatika Profesional [ISTTS](https://s1infpro.stts.edu)

This repo contain 3 DBMS, MySQL, MS SQL, and PostgreSQL

I intended to add more like OracleXE, as ISTTS still teach and having Oracle Workforce program for it's student, but it will be future work

## How To

Clone this project, and run it using podman-compose. This containerfile/dockerfile is tweak specificly for podman and podman compose, as SELINUX is glorious! It's better to have SELINUX for sake security reason rather than not... So please...

```bash
git clone 
cd <to the db folder>
podman-compose up -d --rebuild --force-recreate
```


