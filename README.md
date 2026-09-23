# Adonai FotoCine

Site institucional de página única para a Adonai FotoCine — fotografia e filmagem para casamentos, eventos corporativos, ensaios e estúdio.

## Como visualizar

Não há build nem dependências. Basta abrir `index.html` diretamente no navegador (duplo clique), ou servir a pasta com um servidor estático simples, por exemplo:

```bash
python -m http.server 8000
```

e acessar `http://localhost:8000`.

## Estrutura

```
adonai/
├── index.html      # Estrutura da página (hero, serviços, portfólio, contato)
├── styles.css      # Estilos
└── src/imagens/    # Imagens usadas no site
```

## Contato

- Telefone/WhatsApp: (11) 96575-4892
- E-mail: okathecristina@gmail.com

O formulário de contato da seção "Contato" monta um e-mail (`mailto:`) com os dados preenchidos e abre o cliente de e-mail padrão do usuário; não há envio para um backend.
