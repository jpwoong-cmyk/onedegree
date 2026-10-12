MiniMart V4.1: Phone-as-username / Supabase Email+Password authentication.
Backend Edge Function minimart-register-owner v2 is deployed and creates email users with account_name metadata compatible with the unchanged Pacman trigger.
IMPORTANT: The existing owner is a phone-only Auth user and is NOT automatically converted. The first invitation was consumed. Do not attempt to re-register the same number. Existing owner needs an authorized one-time conversion to add an internal email identity while preserving UID and owner mapping.
No Pacman tables or trigger were modified by this update.
