## Configurações gerais
- [x] Bloquear domínios usando arquivos de filtros e hosts
  | Intervalo de atualização de filtro |
  | ---------------------------------- |
  | 24 horas                           |
- [x] Usar o serviço de segurança da navegação do AdGuard
- [x] Usar o serviço de controle parental do AdGuard
- [x] Usar pesquisa segura
  - [x] Bind
  - [x] Duckduckgo
  - [x] Google
  - [x] Pixabay
  - [x] Yandex
  - [x] Youtube
### Configuração de registros
- [x] Ativar registro
- [ ] Tornar anônimo o IP do cliente
  | Rotação de registros de consulta |
  | -------------------------------- |
  | <ul><li>- [ ] Personalizado</li></ul> |
  | <ul><li>- [ ] 6 horas</li></ul> |
  | <ul><li>- [ ] 24 horas</li></ul> |
  | <ul><li>- [ ] 7 dias</li></ul> |
  | <ul><li>- [x] 30 dias</li></ul> |
  | <ul><li>- [ ] 90 dias</li></ul> |

## Configurações de DNS

### Servidor DNS primário
```
https://security.cloudflare-dns.com/dns-query
[/dominio.local/]10.x.y.z
```
- [x] Balanceamento de carga
- [ ] Solicitações paralelas
- [ ] Endereço de IP mais rápido

### Servidores DNS de inicialização
```
1.1.1.2
1.0.0.2
2606:4700:4700::1112
2606:4700:4700::1002
```

## Lista de bloqueio de DNS
| Ativado | Nome | URL da lista |
| ------- | ---- | ------------ |
| <ul><li>- [x] </li></ul> | AdGuard DNS filter | https://adguardteam.github.io/HostlistsRegistry/assets/filter_1.txt |
| <ul><li>- [x] </li></ul> | SM-Bloqueio | https://sm-solucoes.github.io/AdGuard/bloqueio.txt |


## Lista de Permissão de DNS
| Ativado | Nome | URL da lista |
| ------- | ---- | ------------ |
| <ul><li>- [x] </li></ul> | AdGuard DNS filter | https://adguardteam.github.io/HostlistsRegistry/assets/filter_1.txt |
| <ul><li>- [x] </li></ul> | SM | https://sm-solucoes.github.io/AdGuard/filter.txt |
