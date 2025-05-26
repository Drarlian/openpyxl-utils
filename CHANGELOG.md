# 📜 Changelog - openpyxl-utils

Todos os formatos seguem o padrão [Semantic Versioning](https://semver.org/lang/pt-BR/).

---

## [0.0.3] - 2025-05-26
### Fixed
- Corrigidos erros de importação que impediam o funcionamento correto da biblioteca após a instalação via PyPI.

---

## [0.0.2] - 2025-05-18

### Changed
- Melhorada a precisão e performance da função `pegar_dados_intervalo_planilha`.
- Otimizada a função `descobrir_linha_vazia_planilha` para localizar a última linha preenchida de forma mais eficiente.

---

## [0.0.1] - 2025-05-17

### Added
- Publicação inicial da biblioteca no PyPI.
- Funções para:
  - Leitura de dados com `pegar_dados_intervalo_planilha`.
  - Adição de dados com `adicionar_dados_intervalo_planilha` e `adicionar_dados_fim_coluna`.
  - Remoção de dados com `remover_dados_intervalo_planilha`.
  - Atualização de dados e cores com `atualizar_dados_intervalo_planilha` e `atualizar_cor_intervalo_planilha`.
  - Utilitários de planilha: `iniciar_planilha`, `descobrir_linha_vazia_planilha`, `is_merged` e `converter_objeto_para_planilha`.

### Info
- Estrutura modular organizada em `src/openpyxl_utils/`.
- Empacotamento com `pyproject.toml` e suporte ao padrão de build.
- Licença MIT aplicada.
