## Initial

Clone project to your project root folder
```bash
composer create-project simpletine/codeigniter4-starter starter --stability=dev
```
Or
```bash
git clone https://github.com/Simpletine/CodeIgniter4-Starter.git starter
```
Then
```bash
cd starter
``` 

Copy some require file to root folder (Upgrading to v4.4.8)
```bash
composer update
cp vendor/codeigniter4/framework/public/index.php public/index.php
cp vendor/codeigniter4/framework/spark spark
```

Copy `env` file
```bash
cp env .env
```

Run the app, using different port, add options `--port=9000`
```bash
php spark serve
```

---
#### Installation Issue
If you're facing any installation issue, open a discussion in community
