

### ТЗ 

1. Установить и настроить webpack-dev-server.
2. Настроить hot module replacement.
3. Сделать возможность запуска на разных окружениях (dev, prod) c разной конфигурацией (например, убрать HMR на проде).
4. Настроить JSON-server и отображать полученные с него данные.
5. Добавить запуск линтера при комите.
<br>

### Quick start


```bash
npm i
npm i --save-dev ajv
```

development-mode: webpack.config.js
```bash
npm run start-dev
```

production-mode: webpack.prod.js
```bash
npm run start-prod
```  

JSON-server
```bash
json-server --watch db.json
```

commit with ESLint check and fix
```bash
git commit -a -m "commit_message"
```

Page opens at url http://localhost:8081/

<br>




