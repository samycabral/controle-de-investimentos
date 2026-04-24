# 📊 Projeto Controle de Investimentos em FIIs

Planilha desenvolvida para auxiliar no planejamento e controle de investimentos em **Fundos de Investimento Imobiliário (FIIs)**, com cálculo de patrimônio acumulado, dividendos mensais e sugestão de alocação por perfil de investidor.

---

## 🎯 Objetivo

Ajudar o investidor a:
- Simular o crescimento do patrimônio ao longo do tempo
- Calcular os dividendos mensais esperados
- Distribuir o valor investido por tipo de FII de acordo com o perfil

---

## ⚙️ Como usar

1. Abra o arquivo `PROJETO_DE_INVESTIMENTO.xlsx` no Excel
2. Na seção **CONFIGURAÇÕES**, preencha:
   - Seu **salário**
   - A **taxa de rendimento mensal** da sua carteira
3. Na seção **INVESTIMENTO MENSAL**, informe:
   - Quanto deseja investir por mês
   - Por quantos anos pretende investir
   - A taxa de rendimento mensal esperada
4. Escolha seu **perfil de investidor** (Conservador, Moderado ou Agressivo)
5. A planilha calculará automaticamente a distribuição entre os tipos de FII

---

## 📋 Funcionalidades

### Configurações
| Campo | Descrição |
|---|---|
| Salário | Renda mensal do investidor |
| Rendimento Carteira | Taxa de rendimento atual da carteira |
| Sugestão de Investimento | Valor sugerido para investir (calculado automaticamente) |

### Simulação de Cenários
A planilha projeta o patrimônio acumulado e os dividendos mensais esperados em diferentes horizontes de tempo:

| Período | Patrimônio Estimado* | Dividendos Mensais* |
|---|---|---|
| 2 anos | R$ 5.445,53 | R$ 32,67 |
| 5 anos | R$ 16.755,38 | R$ 100,53 |
| 10 anos | R$ 48.656,84 | R$ 291,94 |
| 20 anos | R$ 225.039,68 | R$ 1.350,24 |
| 30 anos | R$ 864.433,93 | R$ 5.186,60 |

*Valores baseados em aporte de R$ 200/mês com taxa de 1,079% a.m.*

---

## 📂 Tipos de FII e Alocação por Perfil

A distribuição do aporte mensal varia conforme o perfil escolhido:

| Tipo de FII | Conservador | Moderado | Agressivo |
|---|---|---|---|
| Papel | 30% | 32% | 50% |
| Tijolo | 50% | 35% | 10% |
| Híbridos | 10% | 8% | 5% |
| FOFs | 10% | 5% | 5% |
| Desenvolvimento | 0% | 10% | 20% |
| Hotelarias | 0% | 10% | 10% |

---

## 🛠️ Tecnologias utilizadas

- Microsoft Excel (fórmulas, gráfico de pizza, validação de dados)

---

## 👤 Autora

Desenvolvido por **Samylla** durante o bootcamp **Excel com IA**,  
realizado em parceria com o **Santander** na plataforma **DIO (Digital Innovation One)**.
