# Componentes

- [documentacion checkbox](https://m2.material.io/components/checkboxes/web)

--

# Documentación


## checkbox
#### Descripción
El código anterior crea un checkbox con una etiqueta descriptiva. La etiqueta ayuda a los usuarios a entender qué opción están seleccionando.

Se genera una serie de checkboxes con etiquetas asociadas. Cada `input` de tipo `checkbox` está enlazado a un `label` a través del atributo `for`, que debe coincidir con el `id` del `input`.

La clase `checkbox` agrupa los elementos y aplica estilos CSS específicos para los checkboxes, personalizando su apariencia y comportamiento cuando son seleccionados o al pasar el mouse sobre ellos.

| clase | descripcion | uso |
| --| -- | --|
| checkbox| checkbox simple | class="checkbox" |
| checkbox_primary | el checkbox toma el color primario | class="checkbox primary |
| checkbox_primary_lighten | el checkbox toma el color primario pero mas claro | class="checkbox primary_lighten |
| checkbox_secondary | el checkbox toma el color secundario | class="checkbox secondary |
| checkbox_secondary_lighten | el checkbox toma el color secundario pero mas claro | class="checkbox secondary_lighten |
| checkbox_tertiary | el checkbox toma el color terciario | class="checkbox tertiary |
| checkbox_tertiary_lighten | el checkbox toma el color terciario pero mas claro | class="checkbox tertiary_lighten |

### Plantilla de ejemplo
```HTML
    <div class="checkbox primary">
        <input type="checkbox" name="checkbox" id="checkbox1">
        <label for="checkbox1">checkbox 1</label>
    </div>
```

- `div`: en el div de ir la clase
- `id` & `for` deben tener el mismo atributo


## Text area

## Input

## Tabla