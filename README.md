# 🎮GameList
Aplicação backend sobre listagens de jogos.

![image](https://github.com/user-attachments/assets/2ca2f916-71ba-43f2-b393-2a723e1e8a68)

## 🛠️Tecnologias utilizadas
- Java
- Spring Boot
- JPA / Hibernate
- Maven

## 🗺️Modelo conceitual
![image](https://github.com/user-attachments/assets/ff2fe0ea-661e-4ee2-b94a-06d92cd0e0c6)

## 📍Endpoints da API
| Rota               | Descrição                                          
|----------------------|-----------------------------------------------------
| GET /games     | Recupera as informações parciais de todos os jogos
| GET /games/{id}   | Recupera todas as informações de um jogo pelo id
| GET /lists     | Recupera as informações das listas
| GET /lists/{listId}/games     | Recupera as informações parciais dos jogos de uma lista pelo id
| POST /lists/{listId}/replacement     | Troca de lugar dois jogos de uma lista pelo id

**EXEMPLO REPLACEMENT REQUEST**
```json
{
    "sourceIndex": 3,
    "destinationIndex": 1
}
```

## 💻Execução do projeto
Pré-requisitos: Java 21

```bash
# Clone o repositório
git clone https://github.com/luis-crsa/ClientCRUD.git

# Acesse a pasta do projeto
cd clientcrud

# Execute o projeto
./mvnw spring-boot:run
```

# 👨‍💻Autor
Luís Cláudio Rodrigues Sarmento
