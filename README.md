# Calculadora CI - PHP

![PHP CI](https://github.com/danielmazo45/mi-calculadora-ci)

Proyecto de calculadora con pruebas unitarias automáticas usando PHPUnit e integración continua con GitHub Actions.

## Integrantes
- **Daniel Rodriguez mazo**

## Repositorio
https://github.com/TU_USUARIO/TU_REPOSITORIO

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

## Ejecución local

```bash
composer install
./vendor/bin/phpunit tests
```
