# Backup Strategy

Documented approach for data durability.

## RPO / RTO
- Hourly snapshots (RPO 1h)
- Restore target under 30 minutes (RTO)

## Verification
- Monthly restore drill
- Checksum validation after every backup
