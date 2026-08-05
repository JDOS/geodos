# GeoDOS
Geo Data Operating System / Sistema de Operação de Dados Geográficos

| Categoria | Formatos/Dados | Operação |
|---|---|---|
| **Vetorial** | SHP, KML, GeoJSON, GeoPackage | Import, visualização, consulta espacial |
| **Raster** | GeoTIFF, MDE, MDT, MDS | Visualização, análise de elevação/superfície |
| **Nuvem de pontos** | LAS, LAZ | Visualização 3D (Potree) |
| **Camadas/Layers** | WMS, WFS, WMTS | Consumo de serviços externos |
| **Modelos de terreno** | MDE, MDT, MDS, curvas de nível | Análise de relevo, declividade, perfil |
| **Imagens** | Ortofoto, satélite | Basemap, análise visual |


Integração com PostGIS + Leaflet + OpenLayer + Maplibre + Potree

## Python
Versão `3.12.x` foi a escolhida devido a compatibilidade com os pacotes e tools GIS.
>https://www.python.org/downloads/release/python-3129/

## Dependências

### GDAL

Instalação GDAL dependência:

Linux:

> `apt-get install -y gdal-bin libgdal-dev`

Windows:

> https://github.com/cgohlke/geospatial-wheels/releases
> Assets -> GDAL-3.x.x-cp312-cp312-win_amd64.whl
> `pip install GDAL-3.x.x-cp312-cp312-win_amd64.whl`


