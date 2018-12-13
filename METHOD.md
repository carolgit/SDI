### Este modelo foi desenvolvido com a junção de práticas aconselhadas pelas especificações técnicas brasileiras para dados espaciais disponibilizadas de forma pública no portal http://www.geoportal.eb.mil.br e o guia de boas práticas para dados espaciais no ambiente web da W3C e OGC https://www.w3.org/TR/sdw-bp/

| ITENS DO MODELO        | O QUE É AVALIADO |
| ------------- |:-------------:|
|Adquirir dados de outras fontes dentro do padrão ET-ADGV.| verificação das fonte de dados utilizadas são de organizações que também alimentam a INDE|
|Manter atualizada a modelagem da infraestrutura de dados espaciais dentro do padrão ET-EDGV e ET-PCDG.| verificação dos códigos fonte dos sistemas de informação geográfica foram modelados segundo as especificações técnicas EDGV e PCDG e se existe documentação desta modelagem que é mantida atualizada|
|Padronizar a nomenclatura de dados espaciais e suas propriedades por temáticas.| verificação da organização das camadas nos servidores de mapas (geoserver) estão por temática|
|Manter dicionário de dados para cada temática| verificação da existencia ou não de dicinário de dados para os sistemas de informação geográfica|
|Usar HTTP URIs para coisas espaciais que sejam únicas e persistentes.| verificação em código fonte se os sistemas de informação geográfica se este possuem entre si um padrão de URI para os dados espaciais e se o servidor de mapas utilizado possui um padrão de URIs|
|Fazer os dados espaciais indexáveis por mecanismos de busca.| verificação em código fonte se os sistemas de informação geográfica se foram desenvolvidas URI's padronizadas reutilizaveis por outras sistemas e se fontes externas utilizadas são confiáveis|
|Unir fontes em conjunto para criar uma rede de dados.| verificação em código fonte se os sistemas de informação geográfica identificam seus links para serem utilizaveis por outros recursos ex: fornecer serviços com geojson|
|Usar codificação espacial que combina com o público-alvo.| verificação em código fonte se os sistemas de informação geográfica utiliza codificação disponibilizam os dados geográficos nos formatos WMS, WFS, GeoJSON e Raster e se o servidor de mapas|
|Providenciar geometrias na Web de forma reutilizável.| verificação em código fonte se os sistemas de informação armazena o dado espacial de forma de supra as necessidades para efetuar queries de localição |
|Providenciar geometrias no nível certo de precisão e tamanho.|verificação em código fonte se os sistemas de informação geográfica se  são salvos junto ao dado espacial especificações de extensão e formato e verificar o mesmo para os dados publicados no servidor de mapas |
|Escolher sistema de coordenadas que se enquadram a suas aplicações.| verificação em código fonte se os sistemas de informação utilizam EPSG:4674 – SIRGAS 2000¹ |
|Providenciar informações de como os valores de coordenada são codificados.| verificar se metadados possuem a descrição do sistema de referências utilizado|
|Descrever posições relativas| verificação em código fonte se os sistemas de informação descreve posições nos links de forma explicita |
|Usar tipos espaciais apropriados para conectar coisas espaciais| verificação em código fonte se os sistemas de informação os relacionamentos são feitos com as "coisas espaciais"² e não da geometria|
|Providenciar informações na mudança de natureza das coisas espaciais/metadados.| verificar se metadados contêm informações sobre a temporalidade de determinada "coisa espacial"|
|Expor dados espaciais por meio de 'APIs de conveniência'.| consegue expor as informações de forma usual para os usuários providênciando os dados espaciais para leitura humana e de máquina|
|Incluir metadados no perfil MGB.| verificar se a formatação dos metadados esta no padrão do perfil MGB |
|Incluir metadados espaciais em metadados do dataset.| verificação nas camadas dos servidores de mapas se estes providênciam link de acesso aos metadados|


¹ "Desde 25 de fevereiro de 2015, o SIRGAS2000 (Sistema de Referência Geocêntrico para as Américas) é o único sistema geodésico de referência oficialmente adotado no Brasil. Entre 25 de fevereiro de 2005 e 25 de fevereiro de 2015, admitia-se o uso, além do SIRGAS2000, dos referenciais SAD 69 (South American Datum 1969) e Córrego Alegre. O emprego de outros sistemas que não possuam respaldo em lei, pode provocar inconsistências e imprecisões na combinação de diferentes bases de dados georreferenciadas." (https://ww2.ibge.gov.br/home/geociencias/geodesia/pmrg/faq.shtm acessado em 19 setembro de 2018)

² Coisa espacial conjunto de informações sobre um local incluindo seu elemento espacial, a geometria. 
