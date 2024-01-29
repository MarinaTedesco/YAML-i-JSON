# YAML-i-JSON

## YAML

[**YAML**](https://yaml.org/) proporciona una solució amigable i efectiva per a la serialització de dades, posant l'èmfasi en la comoditat dels humans en l'àmbit de tots els llenguatges de programació.

La seua prioritat recau en l'ús humà abans que en les necessitats de les aplicacions, destacant la seua simplicitat i llegibilitat.

Aquest format és reconegut com a llenguatge per a tots els llenguatges de programació, oferint una manera universal d'intercanviar dades. La seua sintaxi simple basada en indentació el fa fàcil d'entendre i utilitzar, establint-se com una eina versàtil per a la configuració i l'intercanvi d'informació estructurada.

```
persona:
  nombre: Juan Pérez
  edad: 25
  direccion:
    calle: Calle Principal
    ciudad: Ciudad Ejemplo
    codigo_postal: "12345"
  contacto:
    - tipo: teléfono
      valor: "555-1234"
    - tipo: email
      valor: juan@example.com
```

## JSON

[**JSON**](https://www.json.org/json-es.html) és un format de serialització de dades que facilita l'intercanvi de dades estructurades entre aplicacions i serveis de programari, amb un enfocament prioritari en les necessitats de les aplicacions en lloc de les necessitats humanes.

A més, destaca per la seua lleugeresa en l'intercanvi de dades. La seua simplicitat tant per als humans, a l'hora de llegir i escriure, com per a les màquines, a l'hora d'interpretar i generar, el converteix en una elecció popular.

```
{
  "persona": {
    "nombre": "Juan Pérez",
    "edad": 25,
    "direccion": {
      "calle": "Calle Principal",
      "ciudad": "Ciudad Ejemplo",
      "codigo_postal": "12345"
    },
    "contacto": [
      {
        "tipo": "teléfono",
        "valor": "555-1234"
      },
      {
        "tipo": "email",
        "valor": "juan@example.com"
      }
    ]
  }
}
```

## DIFERÈNCIES

![image](https://github.com/MarinaTedesco/YAML-i-JSON/assets/158061645/fafb7a1f-19a0-43c8-9b62-5308f98bd895)

|  | YAML | JSON |
|   :---  |     :---: |   :---:  |
| **Llegibilitat**	 |  Fàcil de llegir i escriure |  Llegible, però amb més símbols |
| **Sintaxi**  | Basada en indentació  |  Utilitza claus i valors  |
| **Extensibilitat**	 |  Limitada | Més versàtil  |
| **Ús comú**	  | Configuració i documentació | Comunicació web i emmagatzematge de dades   |
| **Admet comentaris**	 |  Sí | No  |
| **Admet objectes de dades com a valors**  | No |  Sí  |



