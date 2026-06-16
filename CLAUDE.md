# Pera-Labs/privacy — HARD RULE

## ASLA PERA DIŞINDAKİ HİÇBİR KULLANICIYLA COMMIT ATMA

Bu repo'ya **sadece `peraautomations`** identity'si commit eder.

- `user.name`  = `peraautomations`
- `user.email` = `peraautomations@pera-labs.dev`

Başka bir identity (kişisel GitHub hesabı, başka çalışan, bot) görürsen
**commit etmeden** düzelt:

```bash
git config user.name "peraautomations"
git config user.email "peraautomations@pera-labs.dev"
```

Yanlış author push'lanmışsa `git filter-branch --env-filter` ile rewrite
+ `git push --force origin main`.

## Repo amacı

Pera-Labs uygulamalarının (PromptDrop, ToneAdapt, vd.) privacy policy +
terms sayfaları + App Store flag'leri. GitHub Pages ile public servis
edilir, ASC `privacyPolicyUrl` buraya bağlıdır.
