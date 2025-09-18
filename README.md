# Site Soluções Ergonômicas

Este é um site estático desenvolvido com HTML, CSS e JavaScript, baseado no site original da Soluções Ergonômicas. O site é totalmente responsivo e inclui todas as funcionalidades principais.

## Estrutura do Projeto

```
site-ergonomia/
├── index.html          # Página inicial
├── empresa.html        # Página sobre a empresa
├── servicos.html       # Página de serviços
├── cursos.html         # Página de cursos online
├── contato.html        # Página de contato
├── css/
│   └── style.css       # Estilos principais
├── js/
│   └── script.js       # Funcionalidades JavaScript
├── images/             # Diretório para imagens
└── README.md           # Este arquivo
```

## Funcionalidades Incluídas

- ✅ Design responsivo (mobile-first)
- ✅ Menu de navegação com toggle mobile
- ✅ Formulário de contato funcional
- ✅ Botão flutuante do WhatsApp
- ✅ Animações suaves de scroll
- ✅ Contador animado nas estatísticas
- ✅ Efeitos de hover e transições
- ✅ Botão "voltar ao topo"
- ✅ Sistema de notificações
- ✅ Validação de formulário

## Como Personalizar

### 1. Informações da Empresa

Edite os seguintes arquivos para alterar as informações da sua empresa:

**Todas as páginas HTML:**
- Altere "Sua Empresa" no título e rodapé
- Substitua "contato@suaempresa.com.br" pelo seu e-mail
- Atualize o CNPJ no rodapé
- Modifique o número do WhatsApp (5512997635589)

### 2. Conteúdo

**index.html:**
- Seção hero: altere o texto principal e descrição
- Seção sobre: modifique a apresentação da empresa
- Seções de serviços e cursos: ajuste conforme seus oferecimentos

**empresa.html:**
- Atualize a história, missão, visão e valores
- Modifique as qualificações e experiências

**servicos.html:**
- Adicione, remova ou modifique os serviços oferecidos
- Ajuste as descrições conforme necessário

### 3. Cores e Design

**Paleta de Cores Atual:**
- **Azul Turquesa:** `#29C4D9` (cor institucional - confiança, inovação)
- **Verde Suave:** `#7CCB92` (equilíbrio, saúde, bem-estar)
- **Amarelo Dourado Claro:** `#F2C94C` (energia, destaque)
- **Branco Neutro:** `#FFFFFF` (clareza, sofisticação)
- **Cinza Grafite:** `#4A4A4A` (profissional, leitura confortável)
- **Cinza Claro:** `#E5E5E5` (discrição, sofisticação)

**Aplicação das Cores:**
- **Header/Menu:** fundo branco com texto em cinza grafite e destaque em azul turquesa
- **Botões CTA:** amarelo dourado com texto branco
- **Seções principais:** fundo branco + blocos em azul turquesa suave
- **Rodapé:** fundo grafite com texto branco
- **Formulários:** fundo cinza claro com campos brancos e bordas verdes

**css/style.css:**
Para alterar a paleta de cores, substitua as cores atuais por suas preferidas:
- `#29C4D9` - Azul Turquesa principal
- `#7CCB92` - Verde Suave para ícones e detalhes
- `#F2C94C` - Amarelo Dourado para botões CTA
- `#4A4A4A` - Cinza Grafite para textos
- `#E5E5E5` - Cinza Claro para fundos suaves
- Fontes: atualmente usa 'Inter' do Google Fonts

### 4. Imagens

Adicione suas imagens na pasta `images/` e atualize as referências nos arquivos HTML:
- `hero-professional.jpg` - Imagem principal do banner
- `professional-portrait.jpg` - Foto do profissional na página "A Empresa"

### 5. WhatsApp

No arquivo `js/script.js` e em todas as páginas HTML, substitua:
```
https://wa.me/5512997635589
```
Por:
```
https://wa.me/SEU_NUMERO_COM_DDI
```

Exemplo: `https://wa.me/5511987654321`

## Como Usar

### 1. Hospedagem Simples

Você pode hospedar este site em qualquer serviço de hospedagem que suporte arquivos estáticos:

- **GitHub Pages** (gratuito)
- **Netlify** (gratuito)
- **Vercel** (gratuito)
- **Hostinger, GoDaddy, etc.** (pagos)

### 2. Testando Localmente

Para testar o site localmente:

1. Abra o arquivo `index.html` diretamente no navegador, ou
2. Use um servidor local simples:
   ```bash
   # Com Python 3
   python -m http.server 8000
   
   # Com Node.js (se tiver o live-server instalado)
   npx live-server
   ```

### 3. Formulário de Contato

O formulário de contato atualmente simula o envio (mostra uma mensagem de sucesso). Para torná-lo funcional, você precisa:

1. **Usar um serviço como Formspree, Netlify Forms, ou EmailJS**
2. **Configurar um backend próprio**
3. **Usar um serviço de e-mail da sua hospedagem**

Exemplo com Formspree:
```html
<form action="https://formspree.io/f/SEU_ID" method="POST">
```

## Customizações Avançadas

### Adicionando Novas Páginas

1. Crie um novo arquivo HTML baseado em uma página existente
2. Adicione o link no menu de navegação de todas as páginas
3. Atualize o JavaScript se necessário

### Integrações

- **Google Analytics:** Adicione o código de tracking no `<head>` de todas as páginas
- **Facebook Pixel:** Similar ao Google Analytics
- **Chat Online:** Integre com Tawk.to, Zendesk, etc.

### SEO

Para melhorar o SEO:

1. Adicione meta descriptions em cada página:
```html
<meta name="description" content="Sua descrição aqui">
```

2. Adicione meta keywords:
```html
<meta name="keywords" content="ergonomia, saúde do trabalhador, AET">
```

3. Configure Open Graph para redes sociais:
```html
<meta property="og:title" content="Soluções Ergonômicas">
<meta property="og:description" content="Especialistas em ergonomia">
<meta property="og:image" content="URL_DA_IMAGEM">
```

## Suporte

Este site foi desenvolvido para ser facilmente customizável. Se você tiver dúvidas sobre como modificar algo específico, consulte:

1. A documentação do HTML/CSS/JavaScript
2. Tutoriais online sobre desenvolvimento web
3. Fóruns como Stack Overflow

## Licença

Este código é fornecido como está, para uso educacional e comercial. Você pode modificar e usar conforme necessário para seu projeto.

