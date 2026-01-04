# Informações de Backup Automático

## 🤖 Sistema de Backup

Este repositório é atualizado **automaticamente** através de um sistema de backup configurado.

### Frequência

- **Agendamento**: Semanal
- **Dia**: Domingo
- **Horário**: 02:00 (GMT-3)

### Como Funciona

1. O sistema baixa automaticamente o site completo
2. Compara com a versão anterior
3. Se houver mudanças, cria um commit
4. Faz push automático para este repositório

### Commits Automáticos

Os commits automáticos seguem o formato:

```
Backup automático - DD/MM/AAAA

- Data: DD/MM/AAAA às HH:MM:SS
- Origem: https://fabraniia-cvhajxry.manus.space
- Tipo: Backup automático semanal
- Status: Atualização detectada
```

### Histórico de Backups

Para ver o histórico completo de backups:

```bash
git log --oneline --all
```

Para ver detalhes de um backup específico:

```bash
git show <commit-hash>
```

### Restaurar Versão Anterior

Para restaurar o site para uma versão anterior:

```bash
# Ver versões disponíveis
git log --oneline

# Restaurar versão específica
git checkout <commit-hash>

# Voltar para versão atual
git checkout main
```

### Backup Manual

O backup também pode ser executado manualmente quando necessário.

---

## 📊 Estatísticas

- **Tamanho médio do backup**: ~28-30 MB
- **Tempo médio de execução**: 10-25 segundos
- **Arquivos monitorados**: HTML, CSS, JavaScript, Imagens

---

## 🔐 Segurança

- ✓ Repositório privado
- ✓ Autenticação via GitHub CLI
- ✓ Versionamento completo
- ✓ Histórico preservado

---

**Última atualização**: 04 de janeiro de 2026
