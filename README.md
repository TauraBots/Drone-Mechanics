# Drone-Mechanics

> Repositório centralizado de modelagem 3D e arquivos de CAD do veículo aéreo não-tripulado (VANT) em desenvolvimento pela equipe **Taura Bots**.

## 📋 Sobre o Projeto

O **Drone-Mechanics** é um repositório dedicado ao armazenamento, versionamento e gerenciamento de todos os arquivos de modelagem 3D, desenhos técnicos e documentação relacionados ao drone desenvolvido pela equipe de competição Taura Bots.

Este repositório centraliza:
- 🎨 Modelos 3D em CAD (estrutura, componentes, montagens)
- 📐 Desenhos técnicos e especificações
- 🖼️ Renderizações e visualizações
- 📝 Documentação técnica dos componentes
- 🔧 Peças para impressão 3D

## 📁 Estrutura do Repositório

```
Drone-Mechanics/
├── 📁 CAD/
│   ├── 📁 fuselagem/           # Componentes da fuselagem
│   ├── 📁 asas/                # Estrutura das asas
│   ├── 📁 trem-de-pouso/       # Sistema de pouso
│   ├── 📁 motores-helices/     # Motorização
│   ├── 📁 controle/            # Sistema de controle
│   └── 📁 eletronica/          # Compartimento eletrônico
├── 📁 impressoes-3d/           # Arquivos para impressão 3D
│   ├── STL/                    # Arquivos STL prontos
│   └── STEP/                   # Arquivos STEP originais
├── 📁 documentacao/            # Especificações e manuais
│   ├── componentes.md          # Lista de componentes
│   ├── materiais.md            # Especificação de materiais
│   └── montagem.md             # Guia de montagem
└── README.md                   # Este arquivo
```

## 🛠️ Ferramentas e Softwares

Os arquivos foram desenvolvidos utilizando:

- **SolidWorks 2024** - Modelagem 3D e montagem

**Formatos de arquivo:**
- `.step` / `.stp` - Formato universal para CAD
- `.stl` - Arquivos para impressão 3D
- `.pdf` - Documentação

## 📥 Como Visualizar os Arquivos

### Opção 1: Softwares CAD Completos
- **SolidWorks 2024** (recomendado) - Acesso via conta Dassault Systèmes
- **FreeCAD** (gratuito) - [freecadweb.org](https://freecadweb.org)
- **Autodesk Viewer** (web) - Visualização online de arquivos

### Opção 2: Visualizadores Gratuitos
- **IronCAD Viewer** - Visualização rápida de modelos 3D
- **Meshmixer** - Visualização e análise de modelos STL
- **Tinkercad** (web) - Visualização e edição simples

### Opção 3: Impressão 3D
- Para imprimir, use os arquivos `.stl` na pasta `impressoes-3d/`
- Softwares de fatiamento (slicing): Cura, PrusaSlicer, Simplify3D

## 🚀 Como Contribuir

### Fluxo de Trabalho

1. **Clone o repositório**
   ```bash
   git clone https://github.com/TauraBots/Drone-Mechanics.git
   cd Drone-Mechanics
   ```

2. **Crie uma branch para sua funcionalidade**
   ```bash
   git checkout -b feature/nome-componente
   ```

3. **Realizando alterações**
   - Atualize os modelos 3D
   - Exporte versões em `.step` e `.stl` quando necessário
   - Adicione documentação relevante

4. **Commit e Push**
   ```bash
   git add .
   git commit -m "Add/Update: descrição da alteração"
   git push origin feature/nome-componente
   ```

5. **Abra um Pull Request**
   - Descreva as mudanças realizadas
   - Adicione screenshots/renderizações se aplicável
   - Aguarde revisão da equipe

### Padrões de Nomenclatura

- Componentes: `componente_versao.<extension>` (ex: `fuselagem_v2.3.f3d`)
- Arquivos exportados: `componente_vX.Y.step` e `componente_vX.Y.stl`
- Commits: `[TIPO]: descrição` (ex: `[ADD]: novo design de asa`, `[FIX]: ajuste de fuselagem`)

## 📖 Documentação Importante

- **[Componentes](documentacao/componentes.md)** - Lista completa de peças e especificações
- **[Materiais](documentacao/materiais.md)** - Especificação de materiais utilizados
- **[Guia de Montagem](documentacao/montagem.md)** - Instruções passo a passo

---

**Última atualização:** Maio de 2026  
**Versão do drone:** v1.0 (em desenvolvimento)
