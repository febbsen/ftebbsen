# Briefing de marketing — Clínica Ancre e Ancre Gym

Levantamento feito em 27/10/2026 a partir de fontes públicas: sites, Instagram (via Apify), YouTube, LinkedIn, imprensa e agregadores de avaliações. Semrush ficou de fora (conta sem unidades de API). Tudo aqui é inferência de fora para dentro; os itens marcados **[confirmar]** precisam de validação da Fer.

---

## 1. Visão geral do grupo

| | Clínica Ancre | Ancre Gym |
|---|---|---|
| Fundação | Set/2018 (8 anos) | Dez/2025 (~10 meses) |
| Sócios | Dra. Júlia Trindade (psiquiatra, RT) e Fernanda Ebbsen | Fernanda, Dra. Júlia e Henrique Noal (coord. técnico) |
| Endereço | Koerich Beira-Mar Office, R. Demétrio Ribeiro 51, salas 402, 614, 615, 715 | Mesmo prédio, sala 1007 (vista para o mar) |
| Site | clinicaancre.com.br (WordPress + Elementor, Stoot) | ancregym.com.br (Astro, Stoot) |
| Instagram | @clinicaancre — 4.834 seguidores, 398 posts | @ancregym — 2.595 seguidores |
| Google | 5,0 com 33 avaliações | 5,0 com 54 avaliações |
| LinkedIn | 76 seguidores (categoria errada: "bem-estar e condicionamento físico") | não encontrado |
| YouTube | canal antigo ("Ancre faz 3 anos") | @ancregym, vídeos do Checkup |
| Facebook | 147 seguidores | não verificado |
| Imprensa | — | Hallo Magazine (dez/2025): "Ancre Health Group", "Healthness", único ecossistema Technogym completo em SC |

Marca guarda-chuva na imprensa: **Ancre Health Group**. Slogan comum: "faz bem pra vida".

---

## 2. Clínica Ancre

### Posicionamento
- Site: "Saúde mental e bem-estar em Florianópolis". Mensagem central: "Não desistir de nenhum paciente, mesmo quando ele mesmo tenha desistido dele".
- Bio do Instagram já mudou o discurso: **"Cuidado integrado para prevenção e longevidade — mente • corpo • comportamento"**. O site ainda não acompanhou essa virada. **[confirmar]** qual é o posicionamento oficial hoje.
- Especialidades listadas: psiquiatria, psicologia, neurologia, nutrição, reumatologia, clínico geral, nutrologia, endocrinologia, neuropsicologia, cardiologia. Tratamento destacado: escetamina para depressão resistente.
- Preço visto no Doctoralia: consulta de cefaleia R$ 500, sem agendamento online. **[confirmar]** ticket médio e se atende convênio.

### Instagram (@clinicaancre)
- Ritmo: 2 a 3 posts por semana. Segue só 25 contas.
- **O que performa**: vídeos com médico falando de um sintoma concreto. Exemplos: "dor no peito no treino" (491 views, 73 likes), "voltar a treinar depois do infarto" (763 views, 100 likes), "chegada da Dra. Joana, neurologista" (109 likes, 24 comentários), "8 anos de Ancre" (96 likes, 18 comentários).
- **O que não performa**: carrosséis institucionais ou reflexivos (6 a 41 likes, zero comentários).
- Conteúdo de cardiologia do esporte (Dr. Aroni) foi republicado na @ancregym e teve 1.653 plays lá. A ponte clínica → academia funciona.

### Problemas encontrados no site
1. Links do rodapé "Nossa História", "Blog Ancre" e "Perguntas Frequentes" apontam para a home. Não existe blog, logo não existe SEO de conteúdo.
2. Texto "Edit Template" vazando na home e na página Sobre.
3. Dois rodapés com dados diferentes: WhatsApp (48) 99191-7883 vs (48) 98833-7883, e lista de salas diferente. **[confirmar]** qual é o número oficial.
4. Avaliações do Google estão como imagens (prints). Google não lê; não gera prova social indexável.
5. Nenhum CTA além do WhatsApp. Sem agendamento online, sem captura de e-mail.
6. Banner de cookies menciona anúncios, o que indica pixel instalado. **[confirmar]** se roda Google Ads ou Meta Ads e com que verba.
7. Páginas de especialidade têm slug pensado para SEO local (ex.: `/reumatologista-florianopolis/`), o que é bom, mas sem dados Semrush não dá para saber se rankeiam.

### Reputação
- Ranking Médicos (neurologia Floripa): Ancre 5,0 com 33 avaliações. Concorrente com mais volume: Dra. Denise Leal, 4,9 com 175.
- Uma reclamação no Reclame Aqui contra a Unimed menciona cancelamento de consulta na Ancre 3 horas antes. Isolado, mas vale saber.

---

## 3. Ancre Gym

### Posicionamento
- "Muito além do convencional". Academia-boutique com medicina + movimento, Technogym Biostrength com IA, Checkup Technogym (40+ indicadores, Wellness Age), app integrado com nutri e fisio, membership limitado, Ancre Experience (acesso avulso para executivos e atletas de passagem).
- Promessa forte no site: "até 30% a mais de resultados no mesmo período". **[confirmar]** fonte dessa alegação; sem fonte, vira risco.
- Formulário de 3 etapas com qualificação por faixa de investimento mensal em saúde (até R$ 800 → acima de R$ 2.401) e depois WhatsApp. Bom desenho de funil. **[confirmar]** onde esses leads caem (Salesforce?) e taxa de conversão lead → avaliação → membro.
- Sem preço e sem página de planos no site. **[confirmar]** preço do membership e do Checkup avulso, número de membros atual, capacidade máxima e churn mensal.

### Instagram (@ancregym)
- Ritmo: cerca de 2 posts por semana. Vídeos com 666 a 1.812 plays.
- **O que performa**: conteúdo humano e com história. "Em 1980 a Ancre Gym já mudava vidas" (75 likes, 15 comentários), história real de aluna (86 likes, 11 comentários), vídeo do cardiologista (73 likes, 1.653 plays), frequência cardíaca em repouso (72 likes, 7 comentários).
- **O que não performa**: textos motivacionais genéricos sobre constância (4 a 16 likes, zero comentários). Cerca de metade dos posts recentes está nessa categoria.

### Problema crítico no site
- **`<meta name="robots" content="noindex, nofollow">` na home e na página do Checkup.** O Google está instruído a não indexar o site. Provavelmente sobrou da versão de homologação. Qualquer esforço de SEO é inútil até remover isso.
- A busca mostra "www.ancregym.com.br" com título "ANCRE GYM" e descrição diferente do site atual. Pode haver versão antiga no `www` ou cache. **[confirmar]** com a Stoot se `www` redireciona para o domínio sem `www`.

### Reputação
- 5,0 com 54 avaliações no Google em menos de um ano. Mais que a clínica em 8 anos. O processo de pedir avaliação funciona na Gym; replicar na clínica.

---

## 4. Leitura rápida: onde está a alavanca

1. **Ancre Gym — remover o noindex hoje.** Custo zero, bloqueio total.
2. **Checkup como produto de entrada.** Já tem landing, vídeo no YouTube e app. É o lead magnet natural: vende sozinho, qualifica e empurra para o membership. Precisa de preço e de agendamento sem passar pelo WhatsApp.
3. **Conteúdo cruzado clínica ↔ gym.** Médico falando de exercício é o que mais engaja nos dois perfis. Montar uma linha editorial fixa "médico da Ancre explica" e publicar nos dois.
4. **Clínica — site parado.** Blog inexistente, links mortos, prova social em imagem, dois WhatsApps. Antes de investir em tráfego, arrumar a casa.
5. **Avaliações.** Clínica com 33 vs Gym com 54. Pedir avaliação no pós-consulta, com link direto.
6. **Alinhar posicionamento.** Instagram da clínica já fala "prevenção e longevidade"; site fala "saúde mental". Imprensa fala "Ancre Health Group". Decidir uma narrativa e propagar.

---

## 5. O que ainda falta (só a Fer tem)

- Faturamento, meta e ticket médio de cada negócio.
- Número de pacientes/mês e de membros da Gym; capacidade; churn.
- Origem dos clientes hoje (indicação, Google, Instagram, convênio, tráfego pago).
- Verba de mídia atual e quem opera (Stoot? interno?).
- CRM: onde caem os leads do formulário da Gym e do WhatsApp da clínica.
- O que já foi tentado e não funcionou.
- Prioridade: crescer a Gym até lotar o membership, ou escalar a clínica, ou os dois?
