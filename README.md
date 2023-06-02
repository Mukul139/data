# data

Decrypt:
openssl aes-256-cbc -d -a -pbkdf2 -in secrets.txt.enc -out secrets.txt.new

Encrypt:
openssl aes-256-cbc -a -salt -pbkdf2 -in secrets.txt -out secrets.txt.enc
