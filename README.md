# CloudDrop

CloudDrop is a streamlined file‑sharing application built with HTML, CSS, and JavaScript, powered by Supabase Storage. It provides a secure and user‑friendly way to upload files and instantly generate shareable links.
Features

    File Uploads: Select files through a clean interface with optional image previews.

    Progress Tracking: Real‑time progress bar and status updates during upload.

    Secure Links: Generates signed URLs that expire automatically after 24 hours.

    One‑Click Copy: Easily copy shareable links to the clipboard.

    Minimalist Design: Modern dark‑themed UI focused on simplicity and usability.

Tech Stack

    Frontend: HTML, CSS, Vanilla JavaScript

    Backend/Storage: Supabase Storage with Row Level Security (RLS) policies

    Deployment: Vercel

Setup

    Create a Supabase project and a storage bucket (e.g., files).

    Configure Row Level Security policies to allow uploads and reads.

    Replace the placeholder SUPABASE_URL and SUPABASE_ANON_KEY in the code with your project values.

    Deploy the app (e.g., via Vercel) and start sharing files.

