# WebGIS - Tavares, RS

WebGIS interativo desenvolvido com Leaflet para visualização de dados geoespaciais do município de Tavares, Rio Grande do Sul.

## 🗺️ Funcionalidades

- **3 Mapas de Fundo (Basemaps)**
  - OpenStreetMap
  - CartoDB Positron
  - Esri World Imagery

- **Busca de Localização**
  - Busca por qualquer cidade/localização
  - Botão rápido para buscar Tavares, RS

- **Camadas GeoJSON**
  - Município de Tavares (contorno)
  - Imóveis Rurais (perímetros)

- **Informações Detalhadas**
  - Popups informativos com todos os atributos das camadas
  - Tabela completa de atributos para imóveis rurais

## 🚀 Como Usar

1. Acesse o WebGIS através do GitHub Pages
2. Use os controles no painel direito para:
   - Buscar localizações
   - Ativar/desativar camadas GeoJSON
   - Trocar o mapa de fundo
3. Clique nos polígonos no mapa para ver informações detalhadas

## 📁 Estrutura do Projeto

```
├── index.html                          # Arquivo principal do WebGIS
├── data/
│   ├── tavares.geojson                # Camada do município de Tavares
│   └── imoveis_rurais_tavares.geojson # Camada de imóveis rurais
├── README.md                           # Este arquivo
└── .gitignore                          # Arquivos ignorados pelo Git
```

## 🛠️ Tecnologias Utilizadas

- **Leaflet** - Biblioteca JavaScript para mapas interativos
- **OpenStreetMap** - Dados de mapa base
- **GeoJSON** - Formato de dados geoespaciais

## 📝 Licença

Este projeto é desenvolvido para fins educacionais e de pesquisa.

## 👤 Autor

Carmen L. M. Tavares

## 🔗 Links

- [Repositório GitHub](https://github.com/CarmenLMTavares/f2w-aula1_piloto_f2w_tavares)
- [GitHub Pages](https://carmenlmtavares.github.io/f2w-aula1_piloto_f2w_tavares/)


