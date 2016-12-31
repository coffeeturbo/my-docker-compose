## устанавливаем новый проект симфони через контейнер докер
docker run --rm -v $(pwd):/app composer/composer create-project symfony/framework-standard-edition src