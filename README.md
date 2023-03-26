# testrp
tar -czf - ./vsc | openssl enc -pbkdf2 -aes-256-cbc -k "123" -in - -out enc_vsc.file
