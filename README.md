# Mapa de Ronda Digital — Grupo Souza Lima

## Publicação
1. Extraia o ZIP.
2. No Netlify, abra o site e faça um deploy manual arrastando a pasta `mapa-ronda-digital` (ou seu conteúdo).
3. Abra a URL HTTPS no Chrome Android com internet.
4. No menu do Chrome, escolha Instalar app/Adicionar à tela inicial.
5. Abra uma vez para o cache ser preparado. Depois teste em modo avião.

## Recursos
- PWA com manifest e Service Worker.
- IndexedDB para salvar automaticamente os dados no aparelho.
- Inclusão e exclusão de pontos de ronda.
- PDF montado localmente em JavaScript, sem bibliotecas ou serviços externos.
- Compartilhamento nativo quando o navegador Android oferece suporte; caso contrário, baixa o PDF.
- Campo de combustível e assinaturas ficam em branco no PDF; não há campo de supervisor nem seção de ocorrências.

## Limitações e validação
O primeiro carregamento e as atualizações exigem internet. O pacote não foi instalado em aparelho Android real nesta etapa; valide instalação, abertura offline, PDF e compartilhamento no dispositivo após o deploy. Limpar dados do Chrome ou desinstalar o navegador pode apagar os dados locais; salve os PDFs importantes.
