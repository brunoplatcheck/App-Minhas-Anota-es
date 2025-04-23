
# 📝 App Minhas Anotações

Aplicativo desenvolvido em **Flutter** com persistência de dados utilizando **SQLite** localmente. O objetivo é permitir que usuários criem, editem e excluam anotações de forma simples, prática e rápida, com interface amigável e intuitiva.

---

## 🚀 Funcionalidades

- ✅ Criar anotações com título e descrição  
- ✅ Editar anotações existentes  
- ✅ Excluir anotações individualmente  
- ✅ Listagem automática das anotações salvas  
- ✅ Armazenamento local com SQLite  
- ✅ Datas formatadas em `pt-BR`

---

## 🛠️ Tecnologias utilizadas

- **Flutter** (SDK)
- **Dart**
- **SQLite** com `sqflite`
- `intl` para formatação de datas

---

## 📂 Estrutura de arquivos

```bash
lib/
├── model/
│   └── Anotacao.dart           # Classe de modelo da anotação
├── helper/
│   └── AnotacaoHelper.dart     # Classe de acesso ao banco SQLite
├── Home.dart                   # Tela principal com CRUD
└── main.dart                   # Entry point do aplicativo
```

---

## ⚙️ Como executar o projeto

1. **Clone o repositório:**

```bash
git clone https://github.com/brunoplatcheck/App-Minhas-Anota-es.git
```

2. **Navegue até o diretório do projeto:**

```bash
cd App-Minhas-Anota-es
```

3. **Instale as dependências:**

```bash
flutter pub get
```

4. **Execute o projeto:**

```bash
flutter run
```

---

## 📌 Dependências principais (`pubspec.yaml`)

```yaml
dependencies:
  flutter:
    sdk: flutter
  sqflite: ^2.3.0
  path: ^1.8.3
  intl: ^0.18.1
```

---

## 📃 Licença

Este projeto está sob a licença **MIT**. Sinta-se livre para usar, estudar e contribuir!

---

## 👨‍💻 Autor

**Bruno Platcheck**  
🔗 [GitHub](https://github.com/brunoplatcheck)
