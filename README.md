MiniMart V4 - Owner Registration
=================================
Citizen: / 
Owner: /?owner=1
Owner registration: on Owner page > Create owner account, phone + 10+ character password + one-time invitation code.
The initial invitation code was given in the chat; keep it private, do not commit it.
Registration creates a Supabase Auth phone-only user and grants MiniMart owner permission using a deployed Edge Function.
Phone number is a username; no SMS ownership verification is performed.
Existing Pacman authentication trigger is unchanged.
The Supabase database migration and Edge Function have already been deployed.
Do not execute schema.sql again.
For future owner invitations, generate a fresh cryptographically random invite, SHA-256 hash it, then insert the hash into minimart.owner_invites using the Supabase SQL Editor.
