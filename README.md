# Projeto de melhoria para furação flow-drill 🚀

---

## 📌 SISTEMA
- **Sistema de Furação FlowDrill** - Linha Antiga (Linha B)

## 📌 RESUMO

### Estado atual 
- A Máquina opera hoje com um valor fixo de distância de avanço. Quando a produção necessita alterar este valor, o software é modificado.
### Problema 
- A ausência desta funcionalidade interfere na produção e entrega das peças, gerando um tempo maior de produção e a ocupação de um funcionário do setor de Automação para as modificações..
### Objetivo 
- O ajuste da distância de avanço estar na mão do operador e da equipe de manutenção, afim de agilizar a produção.

## 📌 MELHORIA
- **Nova funcionalidade**: Ajuste da distância de avanço das ferramentas

## 📌 COMO SERÁ FEITO
- Disponibilizar na tela IHM, Opções pré-definidas para dois modelos de Furação FlowDrill (P/ Conexão Rosca, P/ Conexão Plug,...). E opção de ajuste fino, para quando houver alterações no modelo da ferramenta, disponível apenas a equipe de manutenção.

## ✨ DESENVOLVIMENTO

### Alterações no programa da IHM
- Criada nova tela de configurações com opção rosca/plug e controle de ajuste fino.
- Incluída indicação na template da barra superior - seleção atual e ajuste de + ou - .

### Alterações no programa do CLP
- Criadas as novas variáveis, necessárias a funcionalidade
- Incluída network para lógica da opção selecionada
- Incluída network para mover valores e lógica ajuste
---
*Versões de software utilizados: ISPSoft 3.23, COMMGR 2.11, DOP 4.00.16*
*Modelos de Hardware: CLP Delta AS228P, IHM Delta DOP-107WV 65536 Colors*

*DATA DA IMPLEMENTAÇÃO: 10/04/2026*
- *G:\Fab_II\Automacao\Projetos\Fockink Fábrica 3 - Panambi - RS\FlowDrill\RUN\Projeto CLP*
- *G:\Fab_II\Automacao\Projetos\Fockink Fábrica 3 - Panambi - RS\FlowDrill\RUN\Projeto IHM*

## ✨ IMAGENS

![photo](\photo.png)
![photo1](\photo1.png)
