# OpenWeatherAPI 📱

**OpenWeatherAPI** é um aplicativo em Flutter e Dart que utiliza a API OpenWeatherMap para criar um aplicativo de previsão do tempo. O aplicativo apresenta uma tela inicial com informações meteorológicas atuais e permite aos usuários acessar detalhes de cada previsão.

### Sobre a API ⚙️
A OpenWeatherMap API fornece acesso a dados meteorológicos e informações relacionadas. Aqui está um resumo básico dos principais conceitos e recursos dessa API:

Obtenção de Informações Meteorológicas:

- A API permite recuperar dados meteorológicos atuais, previsões de curto e longo prazo para locais específicos em todo o mundo.
Endpoint de Requisição:

- As requisições são feitas para o endpoint principal da API, geralmente usando URLs como api.openweathermap.org/data/2.5/weather para informações atuais e api.openweathermap.org/data/2.5/forecast para previsões.
Parâmetros de Requisição:

- A API aceita diversos parâmetros, como coordenadas geográficas (latitude e longitude), nome da cidade, código do país, e outros, para especificar o local desejado.
Formato de Resposta:

- As respostas são geralmente fornecidas em formato JSON e contêm uma variedade de informações meteorológicas, como temperatura, umidade, velocidade do vento, descrição do clima, entre outros.
Unidades de Medida:

- É possível especificar as unidades desejadas para os dados retornados, como Celsius ou Fahrenheit para temperatura, metros por segundo ou quilômetros por hora para velocidade do vento, etc.
Chaves de API:

- Para utilizar a OpenWeatherMap API, você precisa de uma chave de API (API key), que é um identificador único associado à sua conta. Essa chave é incluída nas suas requisições para autenticação.
Recursos Adicionais:

- Além das informações meteorológicas básicas, a API oferece recursos adicionais, como dados de UV, dados históricos, mapas meteorológicos, entre outros.


## Dependências Principais 🚀

- **geolocator**: A dependência `geolocator` permite que você obtenha a localização atual do dispositivo. Isso é útil para buscar informações meteorológicas precisas para a localização do usuário.

- **weather**: A dependência `weather` é essencial para fazer solicitações à API WeatherFactory. Ela permite que seu aplicativo busque informações atualizadas sobre o clima e outros recursos da internet.

- **intl**: O `intl` é usado para formatar e manipular datas, números e outros dados internacionais. Isso é útil para apresentar informações de maneira legível e compreensível para o usuário.

- **flutter_bloc** e **equatable**: Essas dependências são usadas para gerenciar o estado do aplicativo usando o padrão BLoC (Business Logic Component). Isso ajuda a manter o código limpo e modularizado, facilitando a manutenção e o teste.

Essas dependências desempenham papéis específicos em seu projeto, melhorando a experiência do usuário e fornecendo funcionalidades essenciais para a integração com a API WeatherFactory e a apresentação de informações meteorológicas.

## Pré-requisitos 📋

Antes de executar o aplicativo, certifique-se de ter instalado o Flutter e suas dependências. Você pode seguir as instruções de instalação [aqui](https://flutter.dev/docs/get-started/install).

## Instalação e Uso 🛠️

1. Clone o repositório em sua máquina local:

```bash
git clone https://github.com/pedrovictormotasilva/open-weather-api.git
```
2. Navegue até o diretório do projeto:
   
```bash
flutter run
```

## Capturas de Tela 📸

Aqui estão algumas capturas de tela do meu aplicativo:

## **Tela Inicial(HomeScreen:**
![weather](https://github.com/pedrovictormotasilva/weatherApi/assets/92291111/5172cadf-5573-4a87-ac32-482382838a64)

  

## **Permissão de localização:**
  
![WhatsApp Image 2024-02-04 at 12 24 17](https://github.com/pedrovictormotasilva/weatherApi/assets/92291111/ba82c488-a644-406e-9b4a-0480dfd2baed)





## Contribuição 🤝

Sinta-se à vontade para contribuir para o desenvolvimento deste projeto. Qualquer contribuição é bem-vinda!

Fork o projeto
- Crie uma nova branch **(git checkout -b feature/sua-feature)**
- Faça commit das suas mudanças **(git commit -m 'Adicione uma nova feature')**
- Envie as mudanças para o repositório remoto **(git push origin feature/sua-feature)**
- Abra um pull request!

## Licença 📄
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE.md para detalhes.

## Contato 📧
- Nome: Pedro Victor Mota Silva.
- Email: motasilvapedrovictor@gmail.com
- GitHub: https://github.com/pedrovictormotasilva
- Instagram: pedrovic_mota
