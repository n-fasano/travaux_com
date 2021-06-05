### This is my application submission to Travaux.com

git clone ... \
cd .../infra

docker-compose build \
docker-compose up -d

#### Tests
docker exec -ti infra_php_1 sh -c "php ./vendor/bin/phpunit tests"

#### Base script
docker exec -ti infra_php_1 sh -c "php index.php"