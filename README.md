# 🎉 Event Buddy

Aplicativo mobile multiplataforma desenvolvido com **React Native (Expo)** e **Firebase**, que permite aos utilizadores:

- Explorar eventos locais
- Guardar eventos como favoritos
- Inscrever-se em eventos e visualizar sua participação
- Alternar entre temas claro e escuro
- Gerir perfil com imagem de utilizador
- Visualizar o local dos eventos via mapa
- Receber notificações locais

---

## 📱 Funcionalidades

### Autenticação
- Login e registo com email e password
- Logout
- Persistência de sessão
- Login com Google (modo de teste via Firebase)

### Eventos
- Listagem de eventos com imagem, título e data
- Pesquisa por nome ou local
- Página de detalhes com:
  - Descrição completa
  - Botões de participação e favoritos
  - Contador de participantes
  - Mapa da localização
  - Notificação 1h antes do evento

### Favoritos
- Lista de eventos favoritos
- Permite remover diretamente da lista
- Sincronização com a página de detalhes

### Perfil
- Dados do utilizador (email e UID)
- Upload de foto de perfil
- Alternância entre modo claro e escuro

---

## 🔧 Tecnologias e Dependências

- **Expo + React Native**
- **Firebase** (Firestore, Authentication, Storage)
- `react-navigation` para navegação com abas e pilha
- `react-native-maps` para visualização de localização
- `expo-notifications` para notificações locais
- `expo-image-picker` para upload de imagem
- `expo-auth-session` para login com Google

---

## 🔒 Notas de Segurança

> Este projeto está a ser desenvolvido no [Expo Snack](https://snack.expo.dev), que **não suporta variáveis de ambiente (.env)**. Por isso, as chaves do Firebase estão incluídas diretamente no código apenas para **fins de teste**.  
> Em ambiente de produção, recomenda-se configurar variáveis de ambiente com segurança.

---

## 📱 Testar no seu telemóvel

Abra o aplicativo **Expo Go** no seu smartphone e escaneie o QR code abaixo:

![QR Code](./assets/qrcode-eventbuddy.png)

---

## 📂 Estrutura básica do projeto

/screens
Home.js
DetalhesEvento.js
Favoritos.js
Perfil.js
Login.js
Signup.js

/context
AuthContext.js
ThemeContext.js

/services
firebaseAuth.js
notificationService.js

/navigation
MainTabs.js
HomeStack.js

/firebaseConfig.js
/styles.js
/app.json
/App.js


---

## ✍️ Autor

**Danylo Borges Naves**  
Desenvolvedor e idealizador do Event Buddy.

---
