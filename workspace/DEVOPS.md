# DEVOPS

## Capabilities

1. **Write down on GitHub**
   - Versionamento com Git
   - Push para repositório remoto
   - Tags de versão (ex.: `v0.1`, `v0.2`)

2. **Deploy on Vercel**
   - Deploy automático a cada push na branch principal
   - Preview deployments em pull requests
   - Deploy de produção em merge para `master`

## Workflow padrão

1. Desenvolver localmente
2. `git add . && git commit -m "..."`
3. `git push origin master`
4. GitHub Actions dispara deploy na Vercel

## Required GitHub Secrets

Configurar no repositório (`Settings -> Secrets and variables -> Actions`):

- `VERCEL_TOKEN`
- `VERCEL_ORG_ID`
- `VERCEL_PROJECT_ID`

## Notes

- Este repo já está conectado ao GitHub.
- O deploy automático depende dos secrets acima.
