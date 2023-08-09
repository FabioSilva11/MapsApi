# Mapbox Custom Location HTML

Este é um exemplo de código HTML que utiliza a biblioteca Mapbox GL JS para exibir um mapa interativo e permite definir a localização inicial do mapa através das coordenadas passadas pela URL.

## Como Usar

1. Faça o download deste arquivo HTML.

2. Abra o arquivo `mapbox-custom-location.html` em um navegador da web.

3. O mapa será exibido na página, usando o estilo "mapbox://styles/mapbox/satellite-streets-v11".

4. Para definir a localização inicial do mapa, você pode passar as coordenadas através da URL. Use os parâmetros de consulta `lat` (latitude) e `lng` (longitude). Por exemplo:

   ```
   [mapbox-custom-location.html?lat=-3.3275&lng=-61.2089](https://fabiosilva11.github.io/MapsApi/?lat=-3.3275&lng=-61.2089)
   ```

   Substitua os valores de `lat` e `lng` pelos valores desejados.

5. O mapa será carregado com o centro definido pelas coordenadas fornecidas na URL.

6. Você pode ajustar o estilo do mapa, o nível de zoom e outros parâmetros diretamente no código HTML, se desejar.

## Requisitos

- Acesso à internet é necessário para carregar os recursos do Mapbox.

## Licença

Este exemplo é fornecido sob a [Licença MIT](LICENSE).
