# Como publicar o site institucional

## O que publicar

A pasta inteira, não tem nada sensível aqui (sem webhook, sem chave, sem
ID de base). `index.html` mais `assets/`.

```
site-institucional/
├── index.html
└── assets/
    ├── logo.png
    ├── logo-branco.png
    └── diagrama-alavanca.png
```

Já existe `site-locus-institucional.zip` (na raiz desta pasta), pronto
para arrastar.

---

## Netlify Drop, caminho recomendado

1. Acesse **[app.netlify.com/drop](https://app.netlify.com/drop)**
2. Arraste esta pasta (ou o `.zip`) para a área indicada
3. Aparece uma URL do tipo `https://algo-aleatorio-123.netlify.app`
4. Crie a conta quando ele oferecer, senão o site expira em algumas horas
5. Em *Site configuration, Change site name*, troque para algo
   memorizável, por exemplo `locus-compras.netlify.app`

**Para apontar o domínio de verdade depois:** em *Domain management,
Add a domain*, digite `locuscompras.com.br` e siga as instruções de DNS
que o Netlify mostrar. É o passo que resolve o item do Roadmap
("index para o domínio puro não serve nada hoje").

**Para atualizar depois de uma alteração:** aba *Deploys*, arraste a
pasta de novo. A URL não muda.

---

## Antes de divulgar

Abrir a URL publicada e conferir em celular de verdade: o WhatsApp, o
Instagram e o link do Diagnóstico levam para onde devem.
