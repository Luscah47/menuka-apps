# Menuka: versões dos apps Android

Fonte da atualização automática dos apps **Menuka** (lojista, `br.com.menuka.painel`) e **Menuka Motoboy** (`br.com.menuka.motoboy`).

- `painel/version.json` e `motoboy/version.json`: a versão mais recente de cada app (o app consulta este arquivo).
- **Releases**: um release por versão (`painel-v1.0.5`, `motoboy-v1.1.2`), com o APK assinado.

Para instalar à mão, baixe o APK do release mais recente do app. O app confere o SHA-256 e a assinatura do APK antes de instalar uma atualização.

Publicado por `deploy/publish-motoboy-apk.mjs` (repositório menukaa). Não edite os arquivos à mão.
