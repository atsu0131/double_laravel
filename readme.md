
## new cms

docker-compose up -d

docker-compose exec app bash
composer create-project --prefer-dist "laravel/laravel=6.*" .

npm install