# Colección de Circuitos Neumáticos

Este repositorio contiene una colección sistemática de circuitos neumáticos para 2 cilindros, implementados usando diferentes métodos de control.

## Estructura

Los circuitos están organizados por secuencia de operación y método de control:
```
2-cylinder-sequences/
└── [SECUENCIA]/
   ├── intuitivo/ (si aplica)
   ├── cascada/
   ├── paso-a-paso/
   └── electro-paso-a-paso/
```

## Circuitos Disponibles

*Esta lista se actualiza automáticamente conforme se añaden circuitos.*

| Secuencia | Intuitivo | Cascada | Paso a Paso | Electro Paso a Paso |
|-----------|---------|---------|-------------|---------------------|
| A- A+ B- B+ | [✅] | [✅] | [✅] | [✅] |
| A- A+ B+ B- | [✅] | [✅] | [✅] | [✅] |
| A- B- A+ B+ | [✅] | [✅] | [✅] | [✅] |
| A- B- B+ A+ | [✅] | [✅] | [✅] | [✅] |
| A- B+ A+ B- | [✅] | [✅] | [✅] | [✅] |
| A- B+ B- A+ | [✅] | [✅] | [✅] | [✅] |
| A+ A- B- B+ | [✅] | [✅] | [✅] | [✅] |
| A+ A- B+ B- | [✅] | [✅] | [✅] | [✅] |
| A+ B- A- B+ | [✅] | [✅] | [✅] | [✅] |
| A+ B- B+ A- | [✅] | [✅] | [✅] | [✅] |
| A+ B+ A- B- | [✅] | [✅] | [✅] | [✅] |
| A+ B+ B- A- | [🔜] | [🔜] | [🔜] | [🔜] |
| B- A- A+ B+ | [🔜] | [🔜] | [🔜] | [🔜] |
| B- A- B+ A+ | [🔜] | [🔜] | [🔜] | [🔜] |
| B- A+ A- B+ | [🔜] | [🔜] | [🔜] | [🔜] |
| B- A+ B+ A- | [🔜] | [🔜] | [🔜] | [🔜] |
| B- B+ A- A+ | [🔜] | [🔜] | [🔜] | [🔜] |
| B- B+ A+ A- | [🔜] | [🔜] | [🔜] | [🔜] |
| B+ A- A+ B- | [🔜] | [🔜] | [🔜] | [🔜] |
| B+ A- B- A+ | [🔜] | [🔜] | [🔜] | [🔜] |
| B+ A+ A- B- | [🔜] | [🔜] | [🔜] | [🔜] |
| B+ A+ B- A- | [🔜] | [🔜] | [🔜] | [🔜] |
| B+ B- A- A+ | [🔜] | [🔜] | [🔜] | [🔜] |
| B+ B- A+ A- | [🔜] | [🔜] | [🔜] | [🔜] |

## Herramientas Utilizadas
- FluidSim Pneumatics
- Diseño según métodos: intuitivo, cascada, paso a paso

## Referencias 

### Método Cascada
- **Explicación detallada:** [Método Cascada Neumática - Jeff Mamut](https://jeffmamut.blogspot.com/p/metodo-cascada-neumatica.html)
- **Ventajas:** Simplificación del diseño, reducción de componentes
- **Aplicaciones:** Ideal para secuencias regulares y sistemas puramente neumáticos

### Método Paso a paso
- **Explicación detallada:** [NEUMATICA: Método Paso a Paso - EDUCATiA](https://educatia.com.co/neumatica-metodo-paso-a-paso/)
