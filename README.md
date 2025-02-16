# ProjetoFajPivot

**Software para controle de pivô de irrigação via Wi-Fi/Bluetooth com dispositivo móvel.**

## Descrição

O ProjetoFajPivot é uma solução desenvolvida para monitorar e controlar sistemas de irrigação por pivô central utilizando dispositivos móveis. A comunicação entre o dispositivo móvel e o sistema de controle do pivô é realizada via Wi-Fi ou Bluetooth, proporcionando flexibilidade e facilidade de uso. Em desenvolvimento pela equipe do curso de agronomia da Faculdade de Jussara Faj.

## Funcionalidades

- 🚀 **Controle Remoto**: Ligue, desligue, controle a vazão de água, velocidade e direção do pivô de irrigação diretamente do seu dispositivo móvel.

## Requisitos

### 🛠 **Hardware**
- ESP32 para comunicação sem fio.
- Driver L298N para controle do motor.
- Dispositivo móvel com suporte a Wi-Fi ou Bluetooth.

### 💻 **Software**
- Plataforma de desenvolvimento [PlatformIO](https://platformio.org/) instalada.
- Ambiente de desenvolvimento compatível (ex: VSCode).

## Instalação

1. **Clone o repositório**:

   ```bash
   git clone https://github.com/Natalco/ProjetoFajPivot.git

- Abra o projeto no PlatformIO:

- Inicie o VSCode.
Navegue até File > Open Folder e selecione a pasta do projeto clonado.
Configure o ambiente:

- Verifique o arquivo platformio.ini para garantir que as configurações correspondem ao seu hardware específico.
Compile e faça o upload do firmware:

- Conecte o ESP32 ao computador.
No PlatformIO, clique em Build para compilar o código.
Após a compilação bem-sucedida, clique em Upload para enviar o firmware ao ESP32.
Uso
Configuração Inicial:

- Após o upload do firmware, reinicie o ESP32.
O dispositivo entrará em modo de configuração, permitindo a conexão via Wi-Fi ou Bluetooth.
Conexão com o Dispositivo Móvel:

- Wi-Fi: Conecte seu dispositivo móvel à rede Wi-Fi gerada pelo ESP32 e acesse o painel de controle através do navegador.
Bluetooth: Utilize o aplicativo móvel fornecido para parear com o ESP32 e acessar as funcionalidades de controle.
Operação:

- Utilize a interface do aplicativo para monitorar o status do pivô e enviar comandos de controle conforme necessário.

- ## Autores

👨‍💻 **[Natalco](https://github.com/Natalco)** – Desenvolvimento e arquitetura do sistema, Backend e Integração com o ESP32 e L298N, Interface de Usuário e comunicação(Em desenvolvimento).
