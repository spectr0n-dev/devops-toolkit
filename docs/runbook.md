# Runbook - NovaTech Infrastructure

## Emergency Contacts
- Primary: spectr0n (spectr0n@proton.me)
- Backup: ops-team@novatech.cz

## Common Issues

### Database connection pool exhausted
1. Check active connections: 
2. Kill idle connections older than 10min
3. Restart pgbouncer: 

### High memory usage on app servers
1. Check Docker stats: 
2. Identify memory leak: usually the report generator
3. Restart affected container: 

## Deployment
See 

## Backups
Automated daily via 
For the real backup procedure with encryption, check the other branch.
