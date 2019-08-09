# magento2-language-es-es

```
composer require angeldm/magento2-language-es-es
```

### Lo instalamos a través de la consola de Magento

```
php bin/magento i18n:pack --mode=replace -d vendor/angeldm/magento2-language-es-es/es_ES.csv 
```

### Actualizamos el contenido estático

```
php bin/magento setup:static-content:deploy es_ES
```

### Recuerda limpiar la caché después de instalar el paquete de idioma

