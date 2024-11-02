# Gerenciador-de-senhas 
Este projeto é um gerenciador de senhas simples desenvolvidoem Python puro. O objetivo
é fornecer uma maneira segura e eficiente de armazenar, gerar e recuperar senhas para
diferentescontas. O programa utiliza criptografia básica para proteger os dados do usuário. 

# Funcionalidades 
Adicionar Senhas: Permite ao usuário adicionar novas senhas, associando-as a um nome de serviço. 

Visualizar Senhas: O usuário pode visualizar suas senhas armazenadas através de uma chave criptografada.

Gerar Senhas: O usuário pode gerar sua propria senhas de acordo com suas preferências. 
# Pré-requisitos 
    Python 3.x instalado 
    
    Bibliotecas: cryptography (pode ser instalada via pip) 

# Primeiro devemos criar o ambiente virtual: 
    Linux 
      python3 -m venv venv 
    Windows 
      python -m venv venv 
# Após a criação do venv vamos ativa-lo: 
    Linux 
      source venv/bin/activate 
    Windows 
      venv\Scripts\Activate 
# Caso algum comando retorne um erro de permissão execute o código e tente novamente:
    Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
