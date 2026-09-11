---
name: reconhecimento-desenho-tecnico-ia
description: >-
  Skill de Inteligência Artificial para identificação e classificação de equipamentos mecânicos a partir de fotos de campo, gerando automaticamente desenhos técnicos industriais coloridos e realistas em 3 vistas ortogonais (Vista Lateral, Vista Frontal e Vista Superior), cotas dimensionais, balões de componentes ❶..❻ e laudos de manutenção no Padrão Mecânica 4.0 IA.
---

# Skill: Reconhecimento de Equipamentos & Desenho Técnico CAD 3 Vistas (Padrão Mecânica 4.0 IA)

## Objetivo
Analisar fotos de intervenções mecânicas em campo (motores elétricos com conjunto de ventilação/hélice axial, bombas centrífugas API 610, válvulas industriais e filtros de atemperação) e sintetizar automaticamente o relatório técnico e a prancha de desenho técnico CAD normatizada com 3 vistas ortogonais fiéis ao equipamento real.

---

## 1. Classificação de Equipamentos

A IA classifica o ativo a partir de 3 fontes combinadas:
1. **Inspeção Visual da Foto Principal (Slot 1)**:
   - Presença de carcaça com aletas azuis e hélice/pás laranjas: **Motor Elétrico com Conjunto de Ventilação**.
   - Presença de voluta espiralada, carcaça bipartida ou flanges de sucção/descarga: **Bomba Centrífuga**.
   - Presença de volante superior, castelo aparafusado e haste: **Válvula Industrial / PSV**.
   - Presença de corpo perfurado cilíndrico e alça de içamento: **Filtro Cesto do Sistema de Atemperação**.
2. **TAG e Nomenclatura**:
   - MOT, VENT, EXAUST, MOTOR, VENTILADOR, HELICE, IMPELIDOR.
   - BC, BOMBA, P-, PUMP.
   - VALV, PSV, XV, V-.
   - FLT, FILTRO, ATEMP.
3. **Descrição Técnica do Serviço**:
   - Detecção de termos como "PDMA", "remoção da tampa da ventoinha", "alinhamento de eixos", "estanqueidade de gaxetas".

---

## 2. Padrões de Representação CAD 3 Vistas

### 2.1 Motor / Conjunto de Ventilação (Hélice Axial)
- **Título da Prancha**: DESENHO TÉCNICO – MOTOR / CONJUNTO DE VENTILAÇÃO
- **Vista Lateral**:
  - Tampa amarela/laranja da ventoinha na extremidade esquerda com callout "Tampa de proteção da ventoinha".
  - Carcaça cilíndrica aletada em azul técnico com linha apontando "Motor elétrico".
  - Olhal de içamento superior em anel azul com linha apontando "Olhal de içamento".
  - Base de sustentação/fixação inferior em cinza com linha apontando "Base de fixação".
  - Eixo retificado com linha apontando "Eixo do motor (acoplamento direto com o ventilador)".
  - Hélice axial laranja de 8 pás com linha apontando "Hélice / Impelidor axial (ventilador)".
  - Linha de centro longitudinal vermelha tracejada.
- **Vista Frontal (Lado do Ventilador)**:
  - 8 pás simétricas a cada 45 graus irradiando do cubo central.
  - Cubo cilíndrico com porca e anel de retenção.
  - Contorno de fundo da carcaça do motor, olhal superior e base.
  - Linhas de centro cruzadas.
- **Vista Superior**:
  - Projeção de topo mostrando tampa da ventoinha, carcaça aletada, caixa de ligação, olhal, eixo e hélice.
  - Cotas dimensionais: LARGURA (APROX.), COMPRIMENTO (APROX.) e DIÂMETRO DO VENTILADOR (APROX.).
- **Principais Componentes**:
  ❶ Tampa de proteção da ventoinha  
  ❷ Motor elétrico  
  ❸ Olhal de içamento  
  ❹ Eixo do motor  
  ❺ Hélice / Impelidor axial (ventilador)  
  ❻ Base de fixação  
- **Aplicação**: Ventilação / Resfriamento de equipamentos e processos industriais.
- **Observações Técnicas**:
  • Desenho ilustrativo, baseado no equipamento da imagem.  
  • Dimensões podem variar conforme fabricante e modelo.  
  • Verificar alinhamento, fixações e condições da hélice.  
  • Realizar inspeções periódicas na tampa de proteção, hélice e mancais.  
  • Manter o equipamento limpo e em boas condições de pintura.
