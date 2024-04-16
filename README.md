# Tutorial de Implementação de Servidor com Windows Server 2019

Bem-vindo ao tutorial de implementação de servidor utilizando o Windows Server 2019! Este projeto tem como objetivo fornecer um guia passo a passo para configurar um servidor funcional capaz de hospedar serviços como FTP, web e compartilhamento de arquivos utilizando o sistema operacional Windows Server 2019.

### Sobre o Projeto

A implementação de servidores é uma parte fundamental do campo de redes de computadores e administração de sistemas. Um servidor bem configurado é essencial para hospedar sites, compartilhar arquivos e oferecer outros serviços na rede local ou na internet.

Este projeto foi desenvolvido como parte da disciplina de Redes de Computadores II, com o intuito de proporcionar aos estudantes uma experiência prática na configuração de servidores utilizando o Windows Server 2019. Ao seguir este tutorial, você aprenderá a instalar e configurar diferentes serviços de servidor em um ambiente controlado de máquina virtual.

### Sobre o Tutorial

Neste tutorial, você encontrará instruções detalhadas desde a preparação do ambiente, incluindo o download e instalação do Windows Server 2019, até a configuração de serviços como FTP, servidor web e servidor de arquivos. Cada seção foi cuidadosamente elaborada para fornecer uma compreensão clara e abrangente do processo de implementação do servidor.

Lembre-se de que este tutorial serve como uma introdução básica à configuração de servidores e que há muitos aspectos mais avançados a serem explorados. Esteja à vontade para experimentar e expandir as configurações conforme sua necessidade e interesse.

Sem mais delongas, vamos começar a explorar a emocionante jornada de implementação de servidores com o Windows Server 2019!

### 1. Preparação do Ambiente

Antes de começarmos a implementação do servidor, precisamos preparar o ambiente.

#### 1.1 Download e Instalação da ISO do Windows Server 2019
- Baixe a imagem ISO do Windows Server 2019 do site oficial da Microsoft.
- Monte a imagem ISO em sua máquina para acessar os arquivos de instalação.

#### 1.2 Criação da Máquina Virtual no VirtualBox
- Abra o VirtualBox e clique em "Novo" para iniciar o assistente de criação de máquina virtual.
- Siga as instruções do assistente para definir o nome, tipo e versão da máquina virtual.
- Atribua a quantidade de memória RAM e espaço em disco conforme necessário para o Windows Server 2019.

#### 1.3 Instalação do Windows Server 2019 na Máquina Virtual
- Inicie a máquina virtual e selecione a opção de inicialização a partir da imagem ISO do Windows Server 2019.
- Siga as instruções do assistente de instalação do Windows Server 2019 para concluir o processo de instalação.

### 2. Configuração do Servidor FTP

Vamos agora configurar o servidor FTP para permitir a transferência de arquivos.

#### 2.1 Instalação do Serviço FTP
- Abra o Gerenciador do Servidor no Windows Server 2019.
- Selecione a opção "Adicionar Funções e Recursos" e siga as instruções para instalar o serviço FTP.

#### 2.2 Configuração do Servidor FTP
- Configure as opções de segurança, como autenticação e permissões de acesso, no Gerenciador do Servidor.

### 3. Configuração do Servidor Web

Agora, vamos configurar o servidor web para hospedar sites.

#### 3.1 Instalação do Servidor Web (IIS)
- No Gerenciador do Servidor, selecione "Adicionar Funções e Recursos" e instale o Servidor Web (IIS).

#### 3.2 Criação e Configuração de Sites
- Crie sites no IIS e configure as opções de hospedagem de acordo com suas necessidades.

### 4. Configuração do Servidor de Arquivos

Vamos configurar o servidor de arquivos para compartilhar arquivos na rede.

#### 4.1 Configuração de Compartilhamentos de Arquivos
- No Gerenciador do Servidor, configure os compartilhamentos de arquivos e as permissões de acesso conforme necessário.

### 5. Conclusão

Parabéns! Você concluiu o tutorial de implementação do servidor usando o Windows Server 2019. Lembre-se de documentar suas configurações e considerar futuras expansões ou melhorias para o seu servidor.
