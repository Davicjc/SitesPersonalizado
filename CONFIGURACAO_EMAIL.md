# 📧 Configuração do Sistema de Orçamentos por Email

## Como Funciona

O formulário "Solicite seu Orçamento" agora funciona da seguinte forma:

1. **Cliente preenche o formulário** com seus dados e detalhes do projeto
2. **Cliente clica em "Solicitar Orçamento Gratuito"**
3. **Sistema abre automaticamente** o cliente de email padrão do usuário
4. **Email é pré-preenchido** com todas as informações do formulário
5. **Cliente só precisa clicar "Enviar"** no programa de email

## 🔧 Configuração Necessária

### Passo 1: Emails Configurados ✅

Os emails de destino já estão configurados corretamente no arquivo `scripts/script.js`:

```javascript
const emailDavi = 'davicjc+site@gmail.com';                    // ✅ EMAIL DO DAVI
const emailPaulo = 'paulog25.comercial+site@gmail.com';        // ✅ EMAIL DO PAULO
```

**✅ CONFIGURAÇÃO COMPLETA!** O sistema já está pronto para uso.

### Passo 2: Testando o Sistema

1. Abra o site no navegador
2. Vá até a seção "Solicite seu Orçamento"
3. Preencha todos os campos obrigatórios
4. Clique em "Solicitar Orçamento Gratuito"
5. Verifique se o cliente de email abre com as informações

## 📋 Informações Incluídas no Email

O email gerado automaticamente inclui:

- **Para:** davicjc+site@gmail.com, paulog25.comercial+site@gmail.com
- **Assunto:** "Solicitação de Orçamento - [Tipo de Site]"
- **Nome completo** do cliente
- **Email** do cliente  
- **Telefone/WhatsApp** (se informado)
- **Tipo de site** desejado
- **Descrição detalhada** do projeto

## ✅ Vantagens desta Solução

- ✅ **Sem backend necessário** - funciona apenas com HTML/CSS/JS
- ✅ **Compatível com GitHub Pages** - hospedagem gratuita
- ✅ **Dados estruturados** - todas as informações organizadas
- ✅ **Validação automática** - campos obrigatórios verificados
- ✅ **Feedback visual** - usuário sabe que o email foi preparado
- ✅ **Funciona offline** - não depende de serviços externos

## 🎨 Recursos Visuais

- Validação em tempo real dos campos
- Ícone de email que aparece no botão ao submeter
- Feedback visual com cores (verde = válido, vermelho = inválido)
- Animações suaves no botão de envio

## 📱 Compatibilidade

Funciona em todos os dispositivos que tenham um cliente de email configurado:
- **Desktop:** Outlook, Thunderbird, Mail (Mac), etc.
- **Mobile:** Apps de email nativos do iOS e Android
- **Webmail:** Gmail, Outlook.com (através do navegador)

## 🚀 Próximos Passos

1. Altere o email de destino no código
2. Teste o formulário
3. Publique no GitHub Pages
4. Compartilhe o link do seu site!

---

💡 **Dica:** Mantenha este arquivo para referência futura ou para explicar o sistema para outros desenvolvedores.
