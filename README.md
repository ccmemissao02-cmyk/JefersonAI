# Jeferson AI Android v0.3

Projeto Android completo preparado para compilação automática pelo GitHub Actions.

## Estrutura

- `app/build.gradle` — configuração do aplicativo Android
- `app/src/main` — código, manifesto e recursos
- `build.gradle` — configuração Gradle da raiz
- `settings.gradle` — inclui o módulo `:app`
- `.github/workflows/build-apk.yml` — compilação automática

## Gerar APK

1. Crie um repositório GitHub.
2. Envie TODO o conteúdo deste projeto, mantendo as pastas.
3. Abra a aba **Actions**.
4. Execute **Gerar APK Jeferson AI**.
5. Quando terminar, abra a execução.
6. Na seção **Artifacts**, baixe `JefersonAI-APK`.

O APK será `app-debug.apk`.

## Observação

Esta versão é a base Android funcional da interface. O chat ainda usa resposta local de demonstração; a conexão real com Ollama/FastAPI será a próxima etapa.
