# JLS
JLS: **J**ust **L**earn how to copy, and know when to **S**teal

## Usage

```
git clone https://github.com/codeyu/JLS.git
cd jls
docker build -t codeyu/jls:latest .
docker login index.tenxcloud.com
Username: [your name] 
Password: [your password]
**Login Succeeded**
docker tag codeyu/jls:latest index.tenxcloud.com/codeyu/jls:latest
docker push index.tenxcloud.com/codeyu/jls:latest
```