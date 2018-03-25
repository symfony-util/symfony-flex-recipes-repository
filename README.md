# symfony-flex-recipes-repository
Symfony Flex Server Github application repository

* *[Symfony Flex Private Repositories](http://fabien.potencier.org/symfony4-flex-private-repositories.html)* [Fabien Potencier](http://fabien.potencier.org/)
November 23, 2017

## [Create recipes](https://github.com/symfony/recipes)

## Authorize projects
Authorize projects to use the recipes by adding their project's IDs in  `config.json` (where `PROJECT_ULID` is the value of `composer config extra.symfony.id`):
```
{
    "projects": {
        "PROJECT_ULID": "project's name"
    }
}
```
