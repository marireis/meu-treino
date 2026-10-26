# Meu Treino — aplicativo web para iPhone

Aplicação PWA sem backend, sem mensalidade e sem cadastro.

## Funcionalidades
- Treino dividido de segunda a sexta, com 24 exercícios.
- Marcar separadamente cada série; cada marcação inicia um cronômetro de descanso de **60 segundos**.
- Editar repetições e cargas por exercício, registrar progresso por dia e finalizar treinos.
- Histórico local, exportação JSON e links para vídeos demonstrativos (busca no YouTube).
- Pode ser adicionada à tela inicial do iPhone e carregar o aplicativo offline após o primeiro acesso. Os vídeos precisam de internet.

## Hospedagem gratuita (Netlify)
1. Descompacte o arquivo ZIP deste projeto.
2. Abra https://app.netlify.com/drop e entre na sua conta gratuita.
3. Arraste **a pasta `treino-fit-pwa` inteira** para a área de publicação. (Se o seu navegador não aceitar pastas, use a área de deploy com o arquivo ZIP.)
4. Copie o endereço HTTPS fornecido pela Netlify.
5. No iPhone, abra o link pelo **Safari**, toque em **Compartilhar** → **Adicionar à Tela de Início** → **Adicionar**.

O deploy público **não está incluído** no arquivo: publicar depende de autenticação na conta de hospedagem.

## Dados e limitações
Os dados são armazenados no `localStorage` do navegador, **não** sincronizam entre aparelhos, perfis ou instalações, e podem ser perdidos ao limpar dados do Safari. Use **Histórico → Exportar dados** para obter um backup. O app não é prontuário médico ou prescrição individualizada. O cronômetro é baseado em horário real e se corrige quando o app volta do segundo plano, mas alertas podem não tocar com a tela bloqueada no iPhone.
