**SINALIZADOR DE EXTRATOS BANCÁRIOS**

A organização e conciliação de múltiplos extratos bancários em formato PDF (Conta Corrente e Aplicação) é um processo manual e demorado. 
O analista precisa identificar, rastrear e destacar transações específicas (como Tarifas, Resgates, Aplicações e Rendimentos) que estão espalhadas por diversos arquivos.

**O que ele faz:**
-Leitura e Classificação: O script lê os PDFs e os classifica em Conta Corrente ou Aplicação.
-Processamento de Pares: Identifica e concilia automaticamente transferências de valores entre as contas (Ex: um Resgate na Aplicação é rastreado até o crédito na Conta Corrente, e ambos são destacados).
-Sinalização Visual: Aplica highlights coloridos diretamente no PDF original nas linhas das transações encontradas.
-Organização Final: Salva os arquivos processados em pastas estruturadas (RECEITA, DESPESA, TARIFA), organizadas pelo dia da transação, garantindo que o extrato final já esteja pronto para auditoria.

**Bibliotecas:**
PyMuPDF (fitz) – Biblioteca essencial para manipulação de PDF (leitura de texto, busca e aplicação de destaques em coordenadas).
Shutil e pathlib – Utilizados para a gestão da estrutura de pastas de saída e limpeza.

**Observações finais:**
Este código foi pensado pra resolver um problema da minha rotina e de um contexto bancário específico, talvez não funcione pra você.

**Acesso:** https://colab.research.google.com/drive/1EHoIUYf4xaCdwxgTRmxl2FYxOIQLlFKE?usp=sharing
