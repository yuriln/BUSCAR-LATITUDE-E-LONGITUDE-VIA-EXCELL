# Geolocalização a partir de Endereços - Python
Este código tem como objetivo ler os endereços de uma planilha do Excel, chamar a função encontrar_geolocalizacao para cada endereço e imprimir a latitude e longitude correspondentes.

Geolocalização a partir de Endereços - Python
Este script Python utiliza a biblioteca Pandas para ler um arquivo Excel contendo endereços, fazendo consultas à API Nominatim (OpenStreetMap) para encontrar a geolocalização (latitude e longitude) correspondente a cada endereço.

Requisitos
Python 3.x
Pandas
Requests
Instale as bibliotecas Python necessárias usando o seguinte comando:


pip install pandas requests

Como Utilizar

Configuração do Ambiente:

Certifique-se de ter instalado o Python na sua máquina.
Instale as dependências necessárias usando o comando acima.
Preparação do Arquivo Excel:

Prepare um arquivo Excel contendo os endereços na planilha especificada.
Edição do Código:

Substitua 'teste.xlsx' pelo caminho real do seu arquivo Excel.
Altere 'Planilha1' para o nome da sua planilha no arquivo.
Especifique o nome correto da coluna de endereços ('endereços' no exemplo) que contém os endereços a serem consultados.
Execução do Script:

Execute o script Python em um ambiente com acesso à internet.

O script lerá os endereços do arquivo Excel, consultará a API do Nominatim e imprimirá a geolocalização correspondente para cada endereço na saída.
Tratamento de Erros:

O código inclui tratamento de erros para lidar com possíveis problemas, como não encontrar o arquivo, planilha ou coluna especificados.
