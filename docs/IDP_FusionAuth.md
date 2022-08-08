- A IDP da Fusion-Auth, pode ser self-hosted e pode cuidar de toda a autenticação com tecnologia OAuth2.0

- Dificuldades:
    - Configuração de endpoints
    - Segurança de certificados
    - Responsabilidade

- Vantagens:
    - Fluxo de recuperação de senha e confirmação de email automatizado
    - Filtro de CORS e limites de erros personalizável
    - Integrações com serviços externos
        - Outros provedores como o Google
        - Aplicativos 2FA 

- Informações básicas que gerencia
    - Data de nascimento
    - Email
    - Nome de Usuário (Pode ser exclusivo)
    - Telefone
    - Linguagem de preferência
    
[Integração Django + FusionAuth](https://fusionauth.io/blog/2020/07/14/django-and-oauth)
![Login Screen](images/IDP_FusionAuth_Login.png)
![Dados do usuário](images/IDP_FusionAuth_UserData.png)