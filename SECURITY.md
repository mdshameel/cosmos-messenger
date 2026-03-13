Security Policy
Supported Versions
VersionSupportedLatest (main branch)✅ Yes Older commits❌ No
Reporting a Vulnerability
Please do NOT open a public GitHub issue for security vulnerabilities.
If you discover a security vulnerability in COSMOS, please report it responsibly:

Go to the GitHub Security tab
Click "Report a vulnerability"
Describe the vulnerability in detail:

Type of issue (e.g. XSS, data exposure, auth bypass)
Steps to reproduce
Potential impact
Suggested fix if you have one



What to Expect

Acknowledgement within 48 hours
Assessment of severity within 5 days
Fix deployed as soon as possible depending on severity
Credit in the release notes if you wish

Scope
In scope

Cross-site scripting (XSS) in chat messages
Unauthorized access to private group messages
Ability to impersonate other users
Supabase RLS policy bypasses exposing private data

Out of scope

Issues requiring physical access to a device
Social engineering attacks
Spam or abuse of the invite code system

Security Notes for Self-Hosters

The Supabase anon key is intentionally public — it is safe to expose as long as Row Level Security (RLS) is enabled on all tables (the schema SQL does this)
Never commit your Supabase service role key to any repository
For production use, tighten the RLS policies beyond the open demo policies provided in cosmos_schema.sql
