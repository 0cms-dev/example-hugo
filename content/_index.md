---
title: "Welcome to 0CMS Hugo"
---

This is the homepage of the 0CMS Hugo example.

## Featured Services
<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 1rem;">
  {{ partial "card.html" (dict "context" (dict "title" "Fast" "description" "Hugo is incredibly fast." "image" "https://placehold.co/600x400")) }}
  {{ partial "card.html" (dict "context" (dict "title" "Flexible" "description" "Flexible content management." "image" "https://placehold.co/600x400")) }}
</div>

## FAQ
{{ partial "accordion.html" (dict "context" (slice 
  (dict "header" "What is Hugo?" "content" "Hugo is a static site generator written in Go.")
  (dict "header" "Is it free?" "content" "Yes, Hugo is open source and free.")
)) }}
