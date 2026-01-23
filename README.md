---
marp: true
theme: default
_class: lead
paginate: true
backgroundColor: #ffffff
color: #5B2C6F

--- 
# ⚡ Alpine.js
### Introduction rapide
 
Présentée par : *Yousra Akajou*  
Encadrée par : *M. Essarraj Fouad* 

---

## C’est quoi Alpine.js ?
Alpine.js est un **micro-framework JavaScript léger** qui permet d’ajouter de l’interactivité directement dans le HTML, sans configuration complexe.

👉 On peut le voir comme un **"jQuery moderne"** ou un **mini Vue.js**, mais beaucoup plus simple.

---

## Pourquoi utiliser Alpine.js ?
- ✅ Très **léger** (~10kb)
- ✅ **Facile à apprendre**
- ✅ Pas de build, pas de configuration
- ✅ Parfait pour des **petites interactions UI**

---

## Comment ça marche ?
Alpine utilise des **attributs HTML** (`x-data`, `x-show`, `x-on`, etc.) pour gérer la logique JavaScript.

Exemple simple :

```html
<div x-data="{ open: false }">
  <button @click="open = !open">Toggle</button>
  <p x-show="open">Hello Alpine 👋</p>
</div>
```

## Cas d’utilisation courants

- Menus déroulants

- Modals

- Tabs

- Dropdowns

- Formulaires interactifs

## Alpine.js vs autres frameworks

| Framework   | Usage                  |
| ----------- | ---------------------- |
| Alpine.js   | Petites interactions   |
| React / Vue | Applications complexes |

