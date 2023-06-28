### Chamada funcional para a API em `curl`.

curl --request POST \
  --url http://localhost:4000/users \
  --header 'Content-Type: application/json' \
  --data '{"query":"query teste{\n\tlist{_id, age,\n  company,\n  email,\n  eyeColor,\n  \n  index,\n  name,\n  phone,\n  picture,\n\tfriends {name}}\n}","operationName":"teste"}'


### Executar o projeto
Frontend: yarn start
Backend: yarn dev


