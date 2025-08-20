# 📘 Projeto Integrador – MenuAcessível

## 1. Nome do Projeto
**Menu Acessível**

---

## 2. Objetivo Geral
Tornar os cardápios de restaurantes e lanchonetes totalmente acessíveis, permitindo que pessoas com deficiência visual, auditiva ou dificuldades de leitura possam acessar as informações de forma independente. O projeto busca unir tecnologia, acessibilidade e inclusão social, garantindo uma experiência igualitária para todos.

---

## 3. Público-Alvo
- Pessoas cegas ou com baixa visão.
- Pessoas surdas.
- Pessoas com dificuldades de leitura ou alfabetização.
- Restaurantes que desejam ampliar acessibilidade e alcançar novos públicos.

---

## 4. Justificativa
Muitas pessoas enfrentam dificuldades em restaurantes por falta de cardápios acessíveis. Este projeto promove inclusão social, melhora a experiência do cliente, garante conformidade com normas de acessibilidade e amplia o alcance comercial dos estabelecimentos.

---

## 5. Funcionalidades Principais
- **Upload de cardápio pelo restaurante**.
- **Conversão automática em múltiplos formatos**:
  - Áudio (síntese de voz para leitura do cardápio).
  - Libras (tradução por avatar animado ou vídeo).
  - Texto simplificado (para pessoas com dificuldades de compreensão).
- **Interface acessível**:
  - PWA (Progressive Web App), acessível via QR Code nas mesas.
  - Alto contraste, ajuste de fonte, personalização de leitura.
- **Feedback dos usuários**: avaliações sobre acessibilidade.
- **Assistente conversacional**: permite perguntas como *“Quais opções sem glúten?”* com resposta em Libras, áudio ou texto simplificado.

---

## 6. Arquitetura Tecnológica
- **Frontend**: PWA em React ou Vue.js.
- **Backend**: Microserviços (Node.js / Python FastAPI).
- **Banco de Dados**: Multitenant (PostgreSQL ou MongoDB).
- **OCR (Reconhecimento Óptico de Caracteres)** para digitalizar cardápios enviados.
- **NLP (Processamento de Linguagem Natural)** para simplificação de textos.
- **IA de tradução em Libras** (integração com API de avatares 3D).
- **Infraestrutura**: hospedagem em nuvem (AWS / Azure / GCP).

---

## 7. Diferenciais de Inovação
- **Menu Inclusivo Dinâmico**: atualizado em tempo real.
- **Integração com Apps de Delivery** (iFood, UberEats, Rappi).
- **Certificação de Inclusão**: selo digital *“Menu 100% Acessível”*.
- **Gamificação**: pontos para usuários que avaliarem acessibilidade.
- **Analytics**: relatórios para restaurantes sobre uso e acessibilidade.

---

## 8. Fluxo de Uso
1. Restaurante faz upload do cardápio (PDF, imagem ou texto).
2. Sistema processa o cardápio (OCR + NLP) e gera versões acessíveis.
3. Usuário acessa via QR Code ou aplicativo.
4. Escolhe formato preferido (áudio, Libras, texto simplificado).
5. Consome o cardápio e deixa feedback.

---

## 9. Estratégia de Impacto
- **Social**: promove inclusão e autonomia a PCDs.
- **Comercial**: amplia clientela e gera diferencial competitivo.
- **Acadêmico**: aplica conceitos de IA, acessibilidade digital e desenvolvimento orientado a serviços.

---

## 10. Modelo de Negócio (Business Model Canvas)
**Proposta de Valor**: Inclusão e acessibilidade digital para restaurantes e clientes.

**Segmentos de Clientes**:
- Restaurantes e lanchonetes.
- Pessoas com deficiência visual, auditiva ou cognitiva.
- Plataformas de delivery.

**Canais**:
- QR Code nas mesas.
- Aplicativo / PWA.
- Integrações com apps de delivery.

**Relacionamento com Clientes**:
- Suporte digital.
- Relatórios personalizados de acessibilidade.
- Certificação de acessibilidade.

**Fontes de Receita**:
- Assinatura mensal de restaurantes.
- Versão freemium (básica gratuita, premium com analytics).
- Parcerias com apps de delivery.

**Recursos Principais**:
- Plataforma digital.
- OCR, NLP e IA de Libras.
- Infraestrutura em nuvem.

**Atividades-Chave**:
- Desenvolvimento da plataforma.
- Manutenção do banco de dados de cardápios.
- Suporte a restaurantes.

**Parcerias-Chave**:
- ONGs e associações de PCDs.
- Restaurantes pilotos.
- Fornecedores de tecnologia de acessibilidade.

**Estrutura de Custos**:
- Hospedagem em nuvem.
- Desenvolvimento e manutenção.
- Licenciamento de APIs de acessibilidade.
- Suporte técnico.

---

## 11. Próximos Passos
1. Construir MVP com OCR + áudio + contraste.
2. Testar em restaurantes pilotos.
3. Implementar Libras via avatar animado.
4. Expandir para delivery e gamificação.

---

## 12. Conclusão
O **MenuAcessível** é mais que um projeto acadêmico: é uma **plataforma SaaS inclusiva** que une tecnologia, acessibilidade e impacto social. Com potencial de mercado e contribuição direta para a inclusão digital, pode transformar a experiência de consumo em restaurantes no Brasil e além.

