# MarioFit — Watchface Amazfit Pace tema Super Mario

Fork do projeto [GreatFit](https://github.com/GreatApo/GreatFit) (MIT License) customizado com tema Super Mario Bros para Amazfit Pace.

## Fase atual: 1 — APK estático

- ✅ Background Mario aplicado
- ⬜ Fonte estilo bloco (Fase 1.5)
- ⬜ Animações por trigger (Fase 2)
- ⬜ Animações contínuas (Fase 3)
- ⬜ Eventos especiais (Fase 4)

## Como compilar (GitHub Actions faz por você)

1. Faça push para a branch `main` ou `master`.
2. A action `Build APK` em `.github/workflows/build.yml` compila automaticamente.
3. APK fica disponível em **Actions → Build APK → último workflow → Artifacts → MarioFit-APK**.

## Como instalar no Pace

```
adb install -r MarioFit-debug.apk
```

Depois, no Pace: deslize até a tela do AmazMod e selecione MarioFit como watchface.

## Créditos

Baseado em GreatFit por GreatApo (https://github.com/GreatApo/GreatFit), licença MIT.
