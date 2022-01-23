# Generate Public SSL Certificates
- Generate DH Params `openssl dhparam -out dhparams.pem 4096`
- Configure `init-letsencrypt.sh` for nip.io/domain
- Make a copy of `app_server_name.inc.example` and add nip.io/domains
- Enable port forward
- Run `init-letsencrypt.sh`