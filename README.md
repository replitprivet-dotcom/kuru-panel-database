# Kuru Panel Database Backup

Auto-backup of the SQLite database for Kuru Panel.

## Files
- `mod_apk_manager.sqlite` — Main database (auto-updated every 5 minutes)
- `backup_info.txt` — Last backup timestamp

## How it works
- On startup: DB is restored from this repo if local DB is missing
- Every 5 min: DB is backed up to this repo automatically
