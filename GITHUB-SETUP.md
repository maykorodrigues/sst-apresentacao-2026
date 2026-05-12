# 🚀 Guia de Setup GitHub Pages — Apresentação SST Card

## ✅ Status Atual

- ✅ Repositório Git inicializado localmente
- ✅ Arquivo HTML pronto (`apresentacao-sucesso-cliente-2026.html`)
- ✅ README.md com documentação
- ✅ Primeiro commit realizado

## 📋 Próximos Passos

### PASSO 1: Criar Repositório no GitHub (5 min)

1. Acesse: **https://github.com/new**
2. Preencha:
   - **Repository name**: `sst-apresentacao-2026`
   - **Description**: "Apresentação interativa — Sucesso do Cliente SST Card"
   - **Visibility**: Public ✅
3. **Não marque** "Initialize this repository with"
4. Clique em **"Create repository"**

### PASSO 2: Conectar Repositório Local ao GitHub (5 min)

Abra PowerShell (Windows) ou Terminal (Mac) e execute:

```powershell
cd C:\Users\mayko\meu-cerebro\01-projetos\consultoria-comercial\clientes\SST_Clinica_Bairro_da_Paz\lucas-cs
```

Substitua `SEU-USUARIO` pelo seu username do GitHub:

```powershell
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/sst-apresentacao-2026.git
git push -u origin main
```

**Exemplo (se seu usuário for "maykorodrigues"):**
```powershell
git remote add origin https://github.com/maykorodrigues/sst-apresentacao-2026.git
git push -u origin main
```

**Nota**: Você pode ser pedido para fazer login. Use seu GitHub username e token pessoal ou SSH key.

### PASSO 3: Ativar GitHub Pages (5 min)

1. Vá para seu repositório: `https://github.com/SEU-USUARIO/sst-apresentacao-2026`
2. Clique em **Settings** (engrenagem no topo)
3. No menu lateral esquerdo, procure por **Pages**
4. Em "Source", selecione:
   - **Branch**: `main`
   - **Folder**: `/ (root)`
5. Clique em **Save**
6. Aguarde 1-2 minutos (GitHub vai processar)

### PASSO 4: Testar o Link (2 min)

A apresentação estará em:
```
https://SEU-USUARIO.github.io/sst-apresentacao-2026
```

**Exemplo:**
```
https://maykorodrigues.github.io/sst-apresentacao-2026
```

Abra no navegador e teste:
- ✅ Slides navegáveis (setas do teclado)
- ✅ Gráficos aparecem corretamente
- ✅ Responsivo em celular

## 🔑 Credenciais GitHub

### Se usar HTTPS (mais fácil)

Quando Git pedir sua senha, use um **Personal Access Token**:

1. Vá para: https://github.com/settings/tokens
2. Clique em **"Generate new token"** > **"Generate new token (classic)"**
3. Selecione escopo: `repo` (acesso completo a repositórios privados e públicos)
4. Copie o token
5. Cole como "senha" quando Git pedir

### Se usar SSH (mais seguro)

Se já tem SSH key configurada, use:
```powershell
git remote add origin git@github.com:SEU-USUARIO/sst-apresentacao-2026.git
```

## 📱 Compartilhar com Rogério

Copie este link e compartilhe:
```
https://SEU-USUARIO.github.io/sst-apresentacao-2026
```

**Exemplo de mensagem:**
```
Oi Rogério, criei a apresentação de Sucesso do Cliente para Lucas.
Você pode acessar aqui: https://seu-usuario.github.io/sst-apresentacao-2026

Funciona em qualquer navegador, no celular também. Pode imprimir como PDF.
```

## 🔄 Atualizações Futuras

Quando quiser atualizar a apresentação:

```powershell
cd lucas-cs/

# Editar o arquivo HTML

git add apresentacao-sucesso-cliente-2026.html
git commit -m "Update: Atualizar dados/números da apresentação"
git push origin main
```

A apresentação online será atualizada automaticamente em ~2 minutos.

## ❓ Troubleshooting

### "fatal: 'origin' does not appear to be a 'git' repository"
Certifique-se de estar na pasta correta:
```powershell
cd C:\Users\mayko\meu-cerebro\01-projetos\consultoria-comercial\clientes\SST_Clinica_Bairro_da_Paz\lucas-cs
```

### "Permission denied (publickey)"
Use HTTPS em vez de SSH:
```powershell
git remote remove origin
git remote add origin https://github.com/SEU-USUARIO/sst-apresentacao-2026.git
git push -u origin main
```

### GitHub Pages não está aparecendo
Aguarde 5 minutos. Se ainda não funcionar:
1. Verifique se o repositório é **Public** (não Private)
2. Verifique se Pages está ativado em Settings > Pages
3. Verifique se o branch é `main`

## 📞 Suporte

Se tiver dúvidas:
- Email: contato@sucessodetodos.com.br
- GitHub Docs: https://docs.github.com/en/pages

---

**Status**: Pronto para push 🚀
**Data**: 12/05/2026
**Arquivo Principal**: `apresentacao-sucesso-cliente-2026.html`
