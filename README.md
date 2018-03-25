# symfony-flex-recipes-repository
Symfony Flex Server Github application repository

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
