# Play Net — Site institucional

Site de página única (landing page) para o provedor de internet **Play Net** —
_"Viva a velocidade do mundo!"_ — de Bocaiuva/MG.

## Conteúdo

- **Hero** com o mote _"A sua internet acaba de chegar!"_ e chamadas para o WhatsApp.
- **Planos** de fibra óptica (Start, Turbo, Master, Ultra).
- **Vantagens** do provedor.
- **Cobertura / Contato** com telefones, endereço e mapa.
- Botão flutuante e links diretos para o **WhatsApp**.

## Dados de contato usados

- Vendas: **(38) 9 9915-3116**
- WhatsApp: **(38) 9 9744-9507**
- Endereço: **Antônio Alves Carneiro, 221 — Califórnia, Bocaiuva/MG**

## Estrutura

```
index.html            Página principal
assets/css/styles.css Estilos
assets/js/main.js     Interações (menu, animações, contador)
assets/img/           Imagens (flyer original)
```

## Como visualizar

Abra o `index.html` no navegador, ou sirva a pasta localmente:

```bash
python3 -m http.server 8080
# acesse http://localhost:8080
```

## Personalização

- **Preços e velocidades dos planos** são ilustrativos — ajuste em `index.html` na seção `#planos`.
- **Cores** da marca ficam nas variáveis CSS no topo de `assets/css/styles.css`.
- Os links do WhatsApp usam o formato `https://wa.me/55DDDNUMERO?text=...`.
