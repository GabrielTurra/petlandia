Como o objetivo do projeto é deixar tudo exposto, a forma de pensar e todo o processo de construção, estou criando esse arquivo para fazer a separação dos Casos de uso.
Como a ideia do projeto é extensa, vou separar isso em níveis (MVP, intermediario, produto completo). 

# MVP
## Micro-serviços: 
    - Usuário
    - Anúncio

## Casos de uso
    - [ ] Deve ser possível criar uma conta na plataforma
    - [ ] Deve ser possível excluir uma conta na plataforma

    - [ ] Deve ser possível criar um anuncio na plataforma
    - [ ] Deve ser possível visualizar anuncios já cadastrados
    - [ ] Deve ser possível editar meus anuncios
    - [ ] Deve ser possível finalizar um anuncio
    - [ ] Deve ser possível filtrar os anuncios por região

### RF - Regra de negócio
    - [ ] O usuário não deve poder se cadastrar com um e-mail duplicado
    - [ ] O usuário não deve poder se cadastrar com um CPF duplicado
    - [ ] Administradores podem excluir anúncios da plataforma
    - [ ] Um anuncio não pode ser criado sem foto
    - [ ] Um anuncio não pode ser criado sem descrição

### RNF
    - [ ] O login deve ser realizado utilizando credenciais (email e senha).
    - [ ] A senha do usuário deve estar criptografada
    - [ ] Os dados da aplicação precisam estar persistidos em um banco PostgreSQL
    - [ ] Todas listas de dados precisam estar paginadas com 20 itens por página
    - [ ] O usuário deve ser identificado por um JWT (JSON Web Token)