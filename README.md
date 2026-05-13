# ConcursoBot — GitHub Pages

## Como publicar

1. Faça upload do `index.html` neste repositório (pode arrastar direto no GitHub)
2. Vá em Settings → Pages → Source: Deploy from branch → main → / (root) → Save
3. Aguarde ~2 min. Sua URL será: https://SEU_USUARIO.github.io/SEU_REPOSITORIO

## IMPORTANTE — antes de publicar

Edite o `index.html` e substitua no trecho JavaScript:

    const SUPA_URL = 'https://SEU_REF.supabase.co';
    const SUPA_KEY = 'SUA_ANON_KEY_AQUI';

pelos valores reais do Supabase (Settings → API).
