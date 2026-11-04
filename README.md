# RJF8 GRADE 9

A Persian, RTL, mobile-responsive learning portal for Grade 9.

## Current foundation

- Dashboard and responsive subject navigation
- 11 subject areas: Math, Science, Persian, Arabic, English, Social Studies, Heavenly Messages, Quran, Defense Preparation, Technology, and Art
- Supabase email/password authentication
- User profiles and progress tracking
- Lesson publishing structure and quiz data structure
- Row Level Security policies for user-owned progress and admin-managed content
- Single-page frontend in `index.html` to keep the project structure compact

## Backend

Supabase project: `gbuomuxrgmombwgsftce`

The initial database schema is applied to the connected Supabase project. The frontend uses the public publishable key only. Never put a Supabase secret/service-role key in browser code.

## Run locally

Open `index.html` through a local static server or deploy it to a static host. It loads Supabase JS v2 from jsDelivr and Vazirmatn from Google Fonts.

## Publish

Enable GitHub Pages for this repository (Settings → Pages → Deploy from a branch → main → /root), or connect it to a static hosting provider. A live URL is not available until hosting is configured.

## Content status

The subject catalogue and backend structures are ready. Lesson notes and quiz banks are not yet populated; they must be authored and reviewed per Grade 9 curriculum before publication.
