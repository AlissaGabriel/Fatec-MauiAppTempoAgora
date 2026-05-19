# Tempo Agora - .NET MAUI

## Sobre o Projeto

Este aplicativo foi desenvolvido utilizando .NET MAUI com o objetivo de consultar informações climáticas em tempo real utilizando APIs externas.

O usuário pode:

* Pesquisar o clima de uma cidade
* Obter sua localização atual
* Visualizar temperatura e sensação térmica
* Ver informações do nascer e pôr do sol
* Visualizar ícones climáticos
* Acessar um mapa climático integrado

O aplicativo consome dados da API OpenWeatherMap e utiliza recursos de geolocalização do dispositivo.

---

## Funcionalidades do Aplicativo

### Consulta de Clima

O usuário pode pesquisar uma cidade e visualizar:

* Temperatura atual
* Temperatura mínima
* Temperatura máxima
* Sensação térmica
* Coordenadas geográficas
* Horário do nascer e pôr do sol
* Condição climática

### Geolocalização

O aplicativo também consegue:

* Obter a localização atual do usuário
* Identificar automaticamente a cidade
* Utilizar GPS do dispositivo

### Ícones Climáticos

O sistema exibe imagens representando as condições climáticas atuais utilizando os ícones da API OpenWeatherMap.

### Mapa Climático

O aplicativo integra um mapa climático utilizando Windy WebView para visualização meteorológica em tempo real.

---

## Conteúdos Aprendidos

Durante o desenvolvimento deste projeto foram aprendidos os seguintes conceitos:

### Interface gráfica com XAML

Uso de componentes como:

* Grid
* Button
* Entry
* Label
* Image
* WebView

### Programação em C#

* Consumo de APIs REST
* Requisições HTTP com `HttpClient`
* Manipulação de JSON
* Conversão de dados
* Tratamento de exceções (`try/catch`)
* Programação assíncrona (`async/await`)
* Manipulação de datas e horários

### Desenvolvimento Mobile com .NET MAUI

* Geolocalização do dispositivo
* Geocoding reverso
* Navegação e atualização dinâmica da interface
* Exibição de imagens online
* Utilização de WebView
* Permissões do dispositivo

### APIs e Bibliotecas Utilizadas

O projeto utilizou:

* OpenWeatherMap API
* Windy Map Embed
* Newtonsoft.Json
* Geolocation API
* Geocoding API

---

## Recursos Implementados

* Pesquisa de clima por cidade
* Obtenção da localização atual
* Conversão de coordenadas em nome da cidade
* Exibição de informações meteorológicas
* Integração com mapa climático
* Ícones dinâmicos do clima
* Tratamento de erros e permissões

---

## Android Manifest

O projeto também exigiu atualização do arquivo `AndroidManifest.xml` para permitir:

* Acesso à internet
* Permissão de localização
* Uso do GPS do dispositivo

Essas permissões foram necessárias para funcionamento correto das APIs e recursos de geolocalização.

---

## Estrutura do Projeto

### Models

* `Tempo.cs`

Responsável pelas propriedades utilizadas para armazenar os dados climáticos.

### Services

* `DataService.cs`

Responsável pelo consumo da API OpenWeatherMap e processamento dos dados recebidos.

### Views

* `MainPage.xaml`
* `MainPage.xaml.cs`

Responsáveis pela interface gráfica e lógica principal do aplicativo.

---

## Consulta Climática

As informações climáticas são obtidas através da API OpenWeatherMap.

---

## Como Executar o Projeto

1. Clone o repositório
2. Abra o projeto no Visual Studio 2026
3. Restaure os pacotes necessários
4. Execute o projeto em um emulador Android ou dispositivo físico

---

## Estrutura dos Arquivos

* `Models/` → Classes de dados
* `Services/` → Comunicação com APIs
* `Views/` → Interfaces gráficas
* `Platforms/Android/AndroidManifest.xml` → Configuração de permissões do Android

---

Projeto desenvolvido para a disciplina de Programação para Dispositivos Móveis II com .NET MAUI.
