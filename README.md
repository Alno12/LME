# Preenchedor de LME (CEAF 2026)

Página web (`index.html`) para preencher o Laudo de Solicitação, Avaliação e Autorização de Medicamentos (LME) e gerar o PDF pronto para imprimir/assinar.

- Escreve sobre o formulário oficial em branco (`lme-2026.pdf`); campos 17 e 23 (assinaturas) ficam em branco.
- Busca nos 344 medicamentos do CEAF (`meds.js`, extraídos do próprio formulário).
- Dados do médico/CNES ficam salvos no navegador; dados do paciente não são guardados.
- Tudo roda localmente no navegador — nada é enviado a servidores.

Uso local: `python3 -m http.server` nesta pasta e abrir http://localhost:8000.
