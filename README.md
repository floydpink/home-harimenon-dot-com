# Home Subdomain for harimenon.com

Static placeholder page for `home.harimenon.com` subdomain.

## Purpose
- Provides public placeholder for `home.harimenon.com`
- Enables Let's Encrypt wildcard certificate validation
- Private services remain local-only

## Deployment
1. Create new GitHub repository: `home-harimenon-com`
2. Upload these files to the repository
3. Enable GitHub Pages in repository settings
4. Add DNS record in Cloudflare:
   ```
   Type: CNAME
   Name: home
   Content: floydpink.github.io
   Proxy: Enabled (orange cloud)
   ```

## Files
- `index.html` - Main placeholder page
- `CNAME` - GitHub Pages custom domain configuration
- `README.md` - This documentation

## Design
Matches the clean, minimal aesthetic of the main harimenon.com site with:
- Similar typography and color scheme
- Responsive design
- Professional appearance
- Clear navigation back to main site
