# verip (somente um treino)
Simples APP que busca a geolocalização do IP

fiz um script executavel que chama meu app (verIp.py), e criei um link dele na pasta /bin
por fim eu posso então abrir o terminal e digitar:

verip ENDEREÇO_IP
------------------------------------------------

Usando a lib requests para conseguir informações basicas do IP a partir de um arquivo JSON,
além do Pais e Continente obtemos Latitude e Longitude, e com esses dados fazemos uma nova busca mais refinada.

Usando a lib: Nominatim do pacote 'geopy' para tentar resgatar informações exatas de local como Cidade e até mesmo Rua. (Aproximadamente)
inclusive uso uma função já pronta e simples que foi coletada em forum de discussão.

A maioria das excessões de erro foram adicionadas, como por exemplo verificação de IP válido.
...porém o app ainda contém bugs e vai simplesmente travar ocasionalmente.

***Mais do que tudo, isto é só um aquecimento em programação e também um aprendizado da plataforma git / github
