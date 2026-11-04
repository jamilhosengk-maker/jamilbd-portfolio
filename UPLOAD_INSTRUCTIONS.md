# \ud83d\ude80 Upload Your Portfolio to cPanel - COMPLETE GUIDE

## \ud83d\udccb Files You Need

Make sure you have ALL these files ready:

| File | Size | Purpose |
|------|------|---------|
| `index_v2.html` | ~20KB | Main portfolio page |
| `founder_journey.jpg` | ~200KB | Your laptop/sunset photo |
| `sunset_portrait.jpg` | ~180KB | Your portrait photo |
| `cafe_work.jpg` | ~205KB | Your cafe working photo |

---

## \ud83d\udee0 Step-by-Step cPanel Upload

### Step 1: Login to cPanel
```
URL: https://jamilbd.me/cpanel
OR: https://your-hosting.com/cpanel
```
- Username: Your cPanel username
- Password: Your cPanel password

### Step 2: Open File Manager
1. Click **Files > File Manager**
2. Navigate to **public_html** folder
3. Check the box "Show Hidden Files (dotfiles)" at the top

### Step 3: Upload Files
1. Click **+ File** button (top left)
2. Upload these files one by one:
   - `index_v2.html` (rename to `index.html`)
   - `founder_journey.jpg`
   - `sunset_portrait.jpg`
   - `cafe_work.jpg`

### Step 4: Set as Default Page
1. Make sure `index.html` is in the root folder
2. Click on `index.html` \u2192 **Set as Default**
3. Wait 5-10 minutes for changes to apply

### Step 5: Test Your Website
Visit: **https://jamilbd.me**
You should see your new portfolio! \ud83c\udf89

---

## \ud83d\udd12 SSL Setup (Important!)

### Option 1: Let's Encrypt (Free)
1. Go to **Security > SSL/TLS**
2. Click **Manage SSL Sites**
3. Select your domain (jamilbd.me)
4. Click **Run AutoSSL** or enable certificate
5. Wait 5-10 minutes

### Option 2: Force HTTPS
1. Go to **Domains > Redirects**
2. Add redirect: `http://jamilbd.me` \u2192 `https://jamilbd.me`
3. Click **Add Redirect**

---

## \ud83d\udcf1 Mobile Optimization

Your website is already mobile-responsive! Test it:
- Open on your phone
- Resize browser window
- Check all sections work properly

---

## \ud83d\udd27 Customization Tips

Want to change anything? Edit `index.html`:

### Change Colors
Find in CSS:
```css
--primary: #00d4aa;    /* Main teal color */
--secondary: #3d8bfd;  /* Blue accent */
--accent: #f0a500;     /* Gold accent */
```

### Update Contact Info
Find in HTML:
```html
<div class="contact-value">jamil@blazetit.com</div>
<div class="contact-value">+880 1XXX-XXXXXX</div>
```

### Add More Photos
Just add more JPG files and reference them in the gallery section!

---

## \ud83d\ude80 Next Steps

Want me to help with:
- [ ] Add contact form with email backend
- [ ] Create blog section
- [ ] Add more project pages
- [ ] Optimize images for faster loading
- [ ] Create favicon and meta tags
- [ ] Set up Google Analytics

Just tell me what you need! \ud83d\udc4b

---

## \ud83d\udcde Need Help?

If you get stuck:
1. Screenshot the error
2. Tell me what step you're on
3. I'll guide you through it!

---

**Ready to launch?** Your portfolio will be live in 10 minutes! \ud83d\ude80
