Tahapan setup SIMRA-API
1. buat folder baru clone project dari https://github.com/solanoize/simra-api
2. https://www.python.org/downloads/release/python-3109/  (install python)

3. masuk ke cmd ke lokasi folder simra-api yang sudah di clone
Jalankan step ini
 1. pip install -r requirements.txt //yang ada pip
 2. python manage.py migrate
 3. python manage.py createsuperuser
       username: admin (bebas yang gampang)
       email: admin@fake.com (bebas yang gampang)
       password: 12345 (bebas yang gampang)
 4. python manage.py runserver

import collection dan environment ke postmen

running jos