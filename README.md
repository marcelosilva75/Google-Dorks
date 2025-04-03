# 🕵️‍♂️ Google Dorks - Pesquisa Avançada

## 🔍 O que são Google Dorks?
Google Dorking é uma técnica avançada de pesquisa que usa operadores especiais para encontrar informações específicas na web. Pode ser utilizada para auditorias de segurança, busca por documentos e indexação de diretórios expostos.

---

## 📌 Operadores e Exemplos

### 1️⃣ **Pesquisa em Sites Específicos**
- `site:` – Restringe a pesquisa a um domínio específico.
```plaintext
site:gov.br "relatório confidencial"
```
🔹 **Explicação:** Retorna páginas do governo brasileiro contendo "relatório confidencial".

---

### 2️⃣ **Pesquisa de Arquivos Específicos**
- `filetype:` ou `ext:` – Filtra por tipo de arquivo.
```plaintext
filetype:pdf "manual de segurança"
```
🔹 **Explicação:** Retorna documentos PDF relacionados à segurança.

---

### 3️⃣ **Busca por Diretórios e Listagens Públicas**
- `intitle:"index of"` – Encontra diretórios acessíveis publicamente.
```plaintext
intitle:"index of" "backup"
```
🔹 **Explicação:** Mostra diretórios contendo backups visíveis publicamente.

---

### 4️⃣ **Pesquisa de Palavras no Título, URL e Texto**
- `intitle:` – Busca palavras no título da página.
- `inurl:` – Filtra URLs que contêm palavras-chave.
- `intext:` – Procura no corpo do texto.
```plaintext
intitle:"login" inurl:admin
```
🔹 **Explicação:** Encontra páginas de login administrativas.

---

### 5️⃣ **Busca por Câmeras e Dispositivos Expostos**
```plaintext
inurl:"view/view.shtml"
```
🔹 **Explicação:** Procura por câmeras de segurança desprotegidas.

---

### 6️⃣ **Descobrindo Bancos de Dados Abertos**
```plaintext
inurl:phpmyadmin "Welcome to phpMyAdmin"
```
🔹 **Explicação:** Localiza painéis do phpMyAdmin acessíveis sem proteção.

---

### 7️⃣ **Procurando por Senhas Vazadas**
```plaintext
filetype:txt intext:"password"
```
🔹 **Explicação:** Busca arquivos `.txt` contendo a palavra "password".

---

## ⚠️ **Aviso Legal**
O uso indevido dessas técnicas pode violar políticas de privacidade e leis de segurança digital. Utilize essas informações apenas para fins educativos e auditorias de segurança autorizadas. 

---

📌 **Referências:**
- [Exploit-DB Google Hacking Database](https://www.exploit-db.com/google-hacking-database)
- [Google Advanced Search Operators](https://support.google.com/websearch/answer/2466433?hl=en)
