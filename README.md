# Jeff Barnes Gallery

Public gallery: https://jeffbarnesgallery.github.io/
Owner studio: https://jeffbarnesgallery.github.io/admin/

The gallery is public. The owner studio requires GitHub sign-in and repository write access before changes can be saved.

## Add a photograph

1. Open the owner studio and choose Sign in with GitHub.
2. Open My gallery, then Photographs.
3. Add a photograph entry, enter its caption and collection, and select/upload its image.
4. Save or publish the entry, following the editor's prompts.
5. Wait for GitHub Pages to republish, then refresh the public gallery.

The photo list is stored in photos.json, and images are stored under photos/. The editor is configured for web-sized JPG, PNG, WebP, and GIF files up to 4 MB. Keep original-resolution images separately. Repository contents and published photographs are public.

Sign-in is provided by Sveltia CMS and an authentication Worker in the owner's Cloudflare account. Secrets are stored encrypted in Cloudflare, never in this repository. Publishing uses GitHub Pages. No custom domain is required.

Only invite trusted editors to this repository. Removing a photograph from the photo list hides it from the gallery, but uploaded files and earlier Git history can remain public.
