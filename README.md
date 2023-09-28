# BackFriend

## Descrição
O BackFriend foi criado durante o curso "Hackatruck: Internet das Coisas" com o objetivo de ajudar as pessoas a manterem uma postura correta durante o dia. É um aplicativo iOS desenvolvido em SwiftUI, que funciona em conjunto com um acelerômetro MPU6050 acoplado nas costas do usuário, e se comunica com um módulo Wi-Fi ESP32. O aplicativo informa ao usuário quando ele está com a postura incorreta, permitindo que ele a corrija.

## Recursos Principais
- Verificação e correção da postura do usuário.
- Integração com um acelerômetro MPU6050 para coleta de dados de postura.
- Comunicação com um módulo Wi-Fi ESP32 para enviar dados para o banco de dados.

## Tecnologias Utilizadas
- Swift e SwiftUI para o desenvolvimento do aplicativo iOS.
- Sensor MPU6050 como acelerômetro para coleta de dados.
- Módulo Wi-Fi ESP32 para comunicação sem fio.
- Banco de dados IBM Cloudant para armazenamento e recuperação de dados de postura.

## Como Usar
1. Clone o repositório do BackFriend para o seu ambiente de desenvolvimento.
2. Abra o projeto no Xcode.
3. Compile e execute o aplicativo no simulador iOS ou em um dispositivo real compatível com SwiftUI.
4. Conecte o acelerômetro MPU6050 ao módulo Wi-Fi ESP32 conforme as instruções fornecidas.
5. O aplicativo começará a monitorar sua postura automaticamente e enviará os dados para o módulo Wi-Fi ESP32.

## Contribuições
Contribuições são bem-vindas! Se você deseja melhorar o BackFriend ou adicionar novos recursos, siga estas etapas:
1. Fork o repositório.
2. Crie uma nova branch para sua contribuição: `git checkout -b minha-contribuicao`.
3. Faça as alterações desejadas e commit-as: `git commit -m 'Adicionei um novo recurso'`.
4. Envie suas alterações: `git push origin minha-contribuicao`.
5. Abra uma solicitação pull para revisão.

## Contato
Para obter mais informações sobre o projeto BackFriend, entre em contato conosco em fabioantoniocaldeiracaldeira@gmail.com.
