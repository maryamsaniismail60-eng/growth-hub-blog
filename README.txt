GROWTH HUB CUSTOM WEBSITE — connected to your existing Blogger blog
Brand: Growth Hub | Learn • Earn • Live Better
Original blog: https://growthhubme.blogspot.com/
Logo: assets/growth-hub-logo.jpeg (updated with your latest supplied logo)
Social links: Instagram https://instagram.com/ihsan_signature | TikTok https://tiktok.com/@ihsansignature | YouTube https://www.youtube.com/@maryamsaniismail

WHAT THIS VERSION DOES
- Public responsive Growth Hub website with your supplied logo and forest-green/lime-green identity.
- Automatically loads public posts from your existing Blogger blog using Blogger's public JSON feed.
- Shows article title, category, date, cover image (when available), summary and a link to read the full post.
- Search and category filtering.
- Responsive layout and social links with platform names/icons.
- The "Write a post" link opens Blogger, so you keep posting where you already post.
- No separate database or Supabase setup is required for this Blogger-connected version.

HOW TO POST
1. Click "Write a post" or open https://www.blogger.com/
2. Sign in to the Google account that owns Growth Hub.
3. Create/edit a post and click Publish.
4. Reload this custom website; the public post feed should update.
Your original blog remains at https://growthhubme.blogspot.com/.

HOSTING
Upload this folder to a static host such as Netlify or GitHub Pages. All files should stay together, including the assets folder. If using Netlify, deploy the extracted folder (or connect the folder's GitHub repository).
Open index.html locally with VS Code Live Server for local preview. Internet is required for Blogger posts and Google Fonts.

IMPORTANT LIMITATIONS
- Posts are still created and edited on Blogger, not inside a separate custom editor. This is intentional so you can keep your existing workflow.
- The public feed only displays posts Blogger makes public. Draft posts do not appear.
- Category names shown come from Blogger post labels. For consistent categories, use labels such as Education and Skills, Personal Growth, Career Development, Digital Skills, Business and Finance, and Everyday Life.
- If Blogger's feed is blocked or unavailable, the site links visitors to the original Blogger blog.
