langhandler
===========

LangHandler for Yii framework

## Installation ##

Установка прямо из репозитория:
`git submodule add git@github.com:stden/langhandler.git application/protected/extensions/langhandler`

```php
<?
...
    // Предварительная загрузка компонент 
    'preload' => ['log', 'ELangHandler'],
...
    // application components
    'components' => [
        // Конфигурация ELangHandler 
        'ELangHandler' => [
            'class' => 'application.extensions.langhandler.ELangHandler',
            'languages' => ['en', 'ru'],
        ],    
...        
```    


