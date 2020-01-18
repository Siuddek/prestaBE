Prawdopodobnie ip bedzie sie roznic od ip w bazie wiec trzeba zmienic jedna rzecz -> wchodzimy na phpmyadmin -> wybieramy baze prestashop_database, szukamy tabeli ps_shop_url i zmieniamy ip na adres kontenera ze sklepem (docker inspect <nazwa_kontenera> i bierzemy ip 

jesli przy wchodzeniu na panel admina bedzie jakas lipa zatrzymujemy na chwile docker compose i u nas lokalnie chodzimy pod /app/cache i usuwamy foldery dev i prod.
