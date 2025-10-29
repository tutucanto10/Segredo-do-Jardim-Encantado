<<<<<<< HEAD
# Segredo-do-Jardim-Encantado
Um jogo de aventura e mistério desenvolvido durante a faculdade! 🌱✨ Em Segredo do Jardim Encantado, você explora um jardim cheio de enigmas enquanto descobre pistas e resolve desafios para avançar na história. Este repo está sendo refeito do zero para evoluir o projeto com novas funcionalidades e visual repaginado. 🚀
=======
# Segredo do Jardim Encantado — Repositório (Skeleton)

Este repositório foi reconstruído **a partir do executável** `jardim_encantado.exe` (GameMaker).  
**Atenção:** o código-fonte GML original **não** pode ser recuperado apenas do `.exe`.  
O que você encontra aqui é um **esqueleto** para versionamento no GitHub: nomes de símbolos (scripts/objetos/salas/ativos)
extraídos do executável e **stubs** `.gml` vazios para você preencher.

## O que foi feito
- Pasta `bin/` com o binário original para referência.
- Pasta `src/scripts/` com *stubs* `.gml` criados a partir de símbolos detectados (ex.: `gml_Script_*`).
- Listagens de símbolos detectados em `docs/symbols.json`.
- `README.md` com instruções de como transformar isso em um projeto GameMaker válido.

## Limitações
- **Não** há lógica GML original aqui. Engines como GameMaker compilam o projeto para um formato binário/bytecode.
- É possível recuperar **alguns nomes** e **recursos**; porém, a **lógica exata** dos eventos (Create/Step/Draw etc.) não vem no `.exe`.
- Se você **possui o projeto original** (`.yyp` + pastas `objects/`, `rooms/`, `sprites/`, `scripts/` etc.), use-o no lugar destes stubs.

## Como prosseguir
1. **Se você tem o projeto original do GameMaker**:  
   - Abra-o no GameMaker e use **File → Export Project (.yyz)**.  
   - Suba o `.yyz` no GitHub ou descompacte e versione as pastas (`.yyp`, `objects`, `rooms`, `sprites`, `scripts`, etc.).
2. **Se você só tem o EXE** (este caso):  
   - Você pode usar ferramentas de inspeção para abrir `data.win` (quando aplicável) e tentar recuperar **recursos**.
   - Substitua os stubs deste repositório por sua reescrita do código GML.
   - Recrie o projeto no GameMaker e aponte para os arquivos corretos.


---

_Gerado automaticamente em 2025-10-25 22:05:27._
>>>>>>> afc64e6 (chore: add skeleton from EXE + stubs)
