# 🍕 Guia de Uso - Sistema de Login da Pizzaria

## ✅ O que foi criado:

1. **Sistema de Autenticação** (`js/auth.js`)
   - Valida nome de usuário e senha
   - Armazena a sessão do usuário
   - Redireciona para página logada
   - Função de logout

2. **Páginas HTML**
   - `login.html` - Página de login
   - `logado.html` - Página do usuário logado
   - `teste-login.html` - Página de teste simplificada

## 🚀 Como acessar:

### Opção 1: Via Localhost (RECOMENDADO)
```
http://127.0.0.1:8000/teste-login.html
```

Ou a página original:
```
http://127.0.0.1:8000/login.html
```

### Opção 2: Via IP da Rede
```
http://10.0.0.82:8000/teste-login.html
```

**NÃO use `file://` - isso não funciona com JavaScript**

## 👤 Usuários de Teste:

| Usuário | Senha |
|---------|-------|
| `admin` | `123456` |
| `usuario` | `senha123` |
| `test` | `test123` |

## 🔑 Como funciona:

1. Digite o usuário e senha
2. Clique em "Entrar"
3. Se correto → Vai para página logada (mostra seu nome)
4. Se errado → Mostra mensagem de erro em vermelho
5. Clique em "Sair" para desconectar

## ⚙️ Servidor Web

O servidor está rodando na porta **8000**

Para parar o servidor:
1. Abra o Gerenciador de Tarefas (Ctrl+Shift+Esc)
2. Procure por "node.exe" ou "powershell"
3. Encerre o processo

Para reiniciar:
```powershell
cd "h:\Meu Drive\COMPARTILHAMENTO DO PROJETO\PASTA PROJETO\TEMPLATE-RestaurantePizza"
npx http-server -p 8000
```

## 🐛 Se não funcionar:

1. Verifique se o servidor está rodando
2. Limpe o cache do navegador (Ctrl+Shift+Delete)
3. Abra a DevTools (F12) e procure por erros no Console
4. Tente recarregar a página (F5)

---
**Criado em:** 25 de novembro de 2025
