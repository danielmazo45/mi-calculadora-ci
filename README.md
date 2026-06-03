# Calculadora CI - PHP

![PHP CI](https://github.com/danielmazo45/mi-calculadora-ci/actions/workflows/php-ci.yml/badge.svg)

## Descripción

Proyecto de calculadora con pruebas unitarias automáticas usando PHPUnit e integración continua con GitHub Actions. Al hacer push a la rama `main`, se ejecuta automáticamente un pipeline que corre las pruebas y verifica que el código funciona correctamente.

## Requisitos previos

- PHP 8.1 o superior
- [Composer](https://getcomposer.org/)

## Instalación

```bash
# Clonar el repositorio
git clone https://github.com/danielmazo45/mi-calculadora-ci.git
cd mi-calculadora-ci

# Instalar dependencias (PHPUnit)
composer install
```

## Ejecución local

```bash
# Ejecutar todas las pruebas
./vendor/bin/phpunit tests
```

## Estructura del Proyecto

```
calculadora-ci/
├── src/
│   └── Calculadora.php        # Lógica de la calculadora
├── tests/
│   └── CalculadoraTest.php    # Pruebas unitarias con PHPUnit
├── .github/
│   └── workflows/
│       └── php-ci.yml         # Pipeline de GitHub Actions
├── composer.json
└── README.md
```

## Operaciones implementadas

| Método         | Descripción                              |
|----------------|------------------------------------------|
| `sumar`        | Suma dos números                         |
| `restar`       | Resta dos números                        |
| `multiplicar`  | Multiplica dos números                   |
| `dividir`      | Divide dos números (lanza excepción si divisor es 0) |

## Integrantes

- **Daniel Rodriguez Mazo**

## Repositorio

https://github.com/danielmazo45/mi-calculadora-ci
