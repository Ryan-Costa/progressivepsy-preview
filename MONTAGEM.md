# Progressive Psy BR · como montar no Waveform

Este site (`index.html`) foi feito só com o que o Waveform já tem: os blocos do editor, o tema da tela **Aparência** e o CSS dos sites (`waveform/site.css`, cópia de `src/components/site/site.css`). Montando como abaixo, o resultado no Waveform é o mesmo da prévia.

Itens marcados com **(exemplo)** foram inventados para a prévia e precisam ser confirmados com a Progressive.

## 1. Cliente

No admin, **Novo cliente**:

- Nome: `Progressive Psy BR`
- Endereço: `progressivepsybr`
- Responsável: quem cuida do perfil, com convite por e-mail

## 2. Aparência

**Cores** (preto e dourado das artes da Progressive)

| Campo | Cor | Uso |
| --- | --- | --- |
| Fundo | `#070807` | preto |
| Superfície | `#121411` | cartões |
| Texto | `#f3eee2` | |
| Texto secundário | `#b8b09c` | |
| Principal | `#f2c661` | dourado claro (palavras em destaque) |
| Destaque | `#d9a033` | dourado (botões e sobretítulos) |
| Texto dos botões | automático | |

**Tipografia**

| Local | Fonte | Tamanho |
| --- | --- | --- |
| Título principal | Orbitron | 130% |
| Títulos das seções | Orbitron | 85% |
| Sobretítulos | Chakra Petch | 110% |
| Menu | Chakra Petch | 110% |
| Texto | Space Grotesk | 105% |
| Botões | Chakra Petch | 105% |

**Arredondamento:** 2 px (cantos retos, como as artes).

**Identidade:** enviar o logo "∞ PROGRESSIVE" como logo e favicon. Sem logo, o site mostra o nome, como na prévia.

## 3. Mídia

Trocar pelas fotos e artes da própria Progressive (fotos das edições, artes de line-up, decoração). Na prévia foram usadas fotos de referência (créditos no rodapé):

| Uso | Arquivo da prévia | O ideal |
| --- | --- | --- |
| Fundo da abertura (foco no centro) | `beach-please-2022-crowd-stage-lights-night.jpg` | foto de pista de uma edição da Progressive |
| Vitrine do evento (2 fotos) | pista decorada, público no palco | as artes do Psyclub vs Progressive |
| Foto do "Sobre" | `boom-festival-2018.jpg` | foto de uma edição ao ar livre |
| Galeria (4 fotos) | palco, cabine, público, decoração | fotos das festas |

## 4. Eventos (menu **Eventos**)

| Data | Título | Local | Horário | Link |
| --- | --- | --- | --- | --- |
| 25/12 | Psyclub vs Progressive · *Christmas Edition* | Fortaleza, CE | 16:00 **(exemplo)** | linktr.ee/ProgressivePsyBR |
| 23/01 **(exemplo)** | Progressive *Sunset* **(exemplo)** | Fortaleza, CE | 16:00 | instagram.com/progressivepsybr |

## 5. Página inicial: seções, nesta ordem

1. **Abertura** (hero)
   - Fundo: foto, foco no centro. Alinhamento: centro. Sombra: forte. Dica de rolagem: ligada.
   - Sobretítulo `Cultura trance · Brasil`; título em duas linhas: `Everything is` e `*progressive*`
   - Subtítulo: `Somos um portal dedicado a promover a cultura psicodélica progressiva: eventos, artistas e tudo o que move a pista.`
   - Botões: `Próximo evento` → `#evento` (principal); `Todos os links` → `https://linktr.ee/ProgressivePsyBR` (contorno)
2. **Vitrine** (showcase), âncora `evento`, menu `Evento`, fotos à direita, 5 s
   - Sobretítulo `25 de dezembro · Fortaleza, CE`, título `Psyclub vs Progressive *Christmas Edition*`
   - Texto: `O Natal mais psicodélico de Fortaleza: Psyclub e Progressive juntos numa edição especial, com Gebra, Focus Mind e mais atrações. Patrocínio oficial: Pitú.` (confirmar o line-up completo)
   - Botão `Ingressos e informações` → linktree
3. **Sobre** (about), âncora `sobre`, menu `O portal`, foto à direita
   - Sobretítulo `O portal`, título `Cultura *psicodélica progressiva*`, os dois parágrafos da prévia
   - Botão `Seguir no Instagram` → `https://www.instagram.com/progressivepsybr/`
4. **Agenda** (agenda), âncora `agenda`, menu `Agenda`: sobretítulo `Agenda`, título `Próximas *pistas*`
5. **Mídias** (media), âncora `canais`, menu `Canais`, sem vídeo em destaque, cartões lado a lado
   - Sobretítulo `Canais`, título `Acompanhe a *cena*`
   - Cartões: Instagram `Instagram` / `Line-ups, artistas e bastidores`; Link `Ingressos e links` / `Tudo num lugar só` → linktree; Link `Threads` / `@progressivepsybr` → `https://www.threads.net/@progressivepsybr`
6. **Galeria** (gallery), âncora `fotos`, menu `Fotos`, layout **grade**: sobretítulo `Na pista`, título `A cena *progressiva*`, 4 fotos com legenda
7. **Faixa de chamada** (cta_banner): título `Produz, toca ou decora? *Chega junto*`, texto `Divulgue seu evento ou seu trabalho no portal. Fale com a gente pelo Instagram.`, botão `Mandar mensagem` → Instagram
8. **Divisor** (divider): onda, 104 px
9. **Contato** (contact), âncora `contato`, menu `Contato`
   - Sobretítulo `Contato`, título `Fale com a *Progressive*`, texto de apoio da prévia
   - Itens: Instagram `progressivepsybr`; Link, rótulo `Links`, `https://linktr.ee/ProgressivePsyBR` (texto exibido `linktr.ee/ProgressivePsyBR`)
   - Botão `Mandar mensagem` → Instagram
10. **Redes sociais** (social_links), centralizado, título `Everything is progressive`: Instagram e Link (linktree)
11. **Rodapé** (footer): texto `Portal da cultura psicodélica progressiva · Brasil`, links `Instagram` e `Links`, voltar ao topo ligado

Depois: **Publicar**.

## Diferenças entre a prévia e o Waveform

- Fontes: na prévia vêm do Google Fonts; no Waveform, do próprio servidor (mesmas famílias).
- A linha "Fotos de referência" no fim da prévia não existe no Waveform: some quando as fotos forem trocadas.
- Threads não está na lista de redes do Waveform: entra como "Link" (ícone de corrente).
