---
hide:
  - navigation
  - toc
---

<div class="ad-hero" markdown="1">
<div class="ad-hero-inner" markdown="1">

<span class="ad-badge">PEI (43675) · Universidade de Aveiro · 2026/2027</span>

# Ad-Omnia

<p class="ad-tagline">Plataforma de Comando Operacional Unificado e Inteligência Preditiva para Gestão de Crises e Emergências</p>

<div class="ad-btn-row">
<a href="milestones/ms1-inception/descricao-projeto/" class="ad-btn ad-btn-primary">Ver Milestones</a>
<a href="https://github.com/Ad-Omnia" class="ad-btn ad-btn-secondary">Código no GitHub</a>
</div>

<span class="ad-wip">🚧&nbsp; isto é WIP — conteúdo em construção</span>

</div>
</div>

<div class="ad-section" markdown="1">

## Resumo { #resumo }

Plataforma de comando e controlo orientada à gestão de grandes eventos, segurança pública e resposta a crises.
Faz a fusão de dados heterogéneos em tempo real numa interface *Common Operational Picture* (COP) unificada
e usa IA preditiva para antecipar riscos e recomendar a afetação de meios.

## Objetivos { #objetivos }

<div class="ad-features-grid" markdown="1">

<div class="ad-feature-card" markdown="1">
<span class="ad-feature-icon">
<svg viewBox="0 0 48 48" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><ellipse cx="24" cy="10" rx="16" ry="6"/><path d="M8 10v12c0 3.3 7.2 6 16 6s16-2.7 16-6V10"/><path d="M8 22v12c0 3.3 7.2 6 16 6s16-2.7 16-6V22"/></svg>
</span>

**Ecossistema de dados unificado**

Fusão de dados abertos e feeds em tempo real numa única base de conhecimento.
</div>

<div class="ad-feature-card" markdown="1">
<span class="ad-feature-icon">
<svg viewBox="0 0 48 48" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><rect x="14" y="14" width="20" height="20" rx="3"/><path d="M14 20H6M14 28H6M42 20h-8M42 28h-8M20 14V6M28 14V6M20 42v-8M28 42v-8"/></svg>
</span>

**Motor de IA preditiva**

Antecipação de riscos com modelos treinados sobre dados sintéticos.
</div>

<div class="ad-feature-card" markdown="1">
<span class="ad-feature-icon">
<svg viewBox="0 0 48 48" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><circle cx="24" cy="24" r="18"/><circle cx="24" cy="24" r="11"/><circle cx="24" cy="24" r="4"/><path d="M24 6v6M24 36v6M6 24h6M36 24h6"/></svg>
</span>

**Interface COP de baixa latência**

Uma imagem operacional comum, sempre atualizada, para quem decide no terreno.
</div>

<div class="ad-feature-card" markdown="1">
<span class="ad-feature-icon">
<svg viewBox="0 0 48 48" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><circle cx="20" cy="28" r="14"/><circle cx="20" cy="28" r="7"/><path d="M20 28l16-16M30 8h8v8"/></svg>
</span>

**Recomendação tática de meios**

Sugestões automáticas de afetação de recursos face ao risco identificado.
</div>

<div class="ad-feature-card" markdown="1">
<span class="ad-feature-icon">
<svg viewBox="0 0 48 48" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><rect x="6" y="6" width="14" height="14" rx="2"/><rect x="28" y="6" width="14" height="14" rx="2"/><rect x="6" y="28" width="14" height="14" rx="2"/><rect x="28" y="28" width="14" height="14" rx="2"/></svg>
</span>

**Arquitetura modular *dual-use***

Componentes independentes, reutilizáveis tanto em contexto civil como de defesa.
</div>

</div>

<!--
  Secção "Arquitetura (rascunho)" retirada daqui — vai passar para uma
  página própria. Fica o código Mermaid guardado como exemplo para
  reaproveitar nesse ficheiro:

  ## Arquitetura (rascunho) { #arquitetura }

  <div class="ad-card ad-arch-card" markdown="1">

  ```mermaid
  flowchart LR
      APIs[APIs externas] --> DBF[(DB Fast)]
      DBF <--> Core
      DBF --> AI
      Plugins <--> Core
      AI <--> Core
      Core <--> DBM[(DB Main)]
      Core <--> Proxy
      Proxy <--> Frontend
  ```

  </div>
-->

## Equipa { #equipa }

<div class="ad-team-grid" markdown="1">

<div class="ad-avatar-card" markdown="1">
<span class="ad-avatar" style="--c1:#2B6FE0;--c2:#0E9E86">FS</span>

**Fernando Santos**

NMEC 124808
</div>

<div class="ad-avatar-card" markdown="1">
<span class="ad-avatar" style="--c1:#0E9E86;--c2:#2EC4AA">MN</span>

**Miguel Neto**

NMEC 125200
</div>

<div class="ad-avatar-card" markdown="1">
<span class="ad-avatar" style="--c1:#8B35E0;--c2:#2B6FE0">DS</span>

**Diogo Silva**

NMEC 125240
</div>

<div class="ad-avatar-card" markdown="1">
<span class="ad-avatar" style="--c1:#2B6FE0;--c2:#A03CFF">GM</span>

**Guilherme Martins**

NMEC 125260
</div>

<div class="ad-avatar-card" markdown="1">
<span class="ad-avatar" style="--c1:#0E9E86;--c2:#8B35E0">BR</span>

**Bernado Reis**

NMEC 126004
</div>

</div>

## Orientação { #orientacao }

- Fábio Coutinho
- Ricardo Figueiredo
- Advisors: Arnaldo Oliveira, Nuno Borges de Carvalho

!!! note "Estado do projeto"
    Fase atual: **Inception (MS1)**.

<div class="ad-full-bleed ad-cta" markdown="1">
<div class="ad-cta-inner" markdown="1">

### Pronto para explorar?

Consulta os milestones do projeto ou acompanha o progresso no repositório.

<div class="ad-btn-row">
<a href="milestones/ms1-inception/descricao-projeto/" class="ad-btn ad-btn-primary">Ver Milestones</a>
<a href="https://github.com/Ad-Omnia" class="ad-btn ad-btn-secondary">GitHub</a>
</div>

</div>
</div>