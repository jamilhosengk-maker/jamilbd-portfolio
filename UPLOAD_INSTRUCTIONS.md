# \ud83d\ude80 Jamil Hosen Portfolio - Upload Guide

## \u2705 Your Package is Ready!

**File:** `jamilbd_portfolio.zip` (687 KB)

---

## \ud83d\udce4 How to Download the Files

### Option 1: Direct Download (If Available)
```bash
# On your local machine, run:
scp ubuntu@YOUR_SERVER_IP:/home/ubuntu/.hermes/cache/scratch/jamilbd_portfolio.zip ./
```

### Option 2: Copy Files Manually
Download each file from the server:
- `/home/ubuntu/.hermes/cache/scratch/index_v2.html`
- `/home/ubuntu/.hermes/cache/scratch/founder_journey.jpg`
- `/home/ubuntu/.hermes/cache/scratch/sunset_portrait.jpg`
- `/home/ubuntu/.hermes/cache/scratch/cafe_work.jpg`

---

## \ud83d\udee0 Step-by-Step Upload to cPanel

### Step 1: Login to cPanel
```
URL: https://jamilbd.me/cpanel
Username: Your cPanel username
Password: Your cPanel password
```

### Step 2: Open File Manager
1. Click **Files** section
2. Click **File Manager**
3. Navigate to **public_html** folder

### Step 3: Delete Old Files (If Any)
- Right-click on `index.html` (if exists)
- Click **Delete**
- Confirm deletion

### Step 4: Upload New Files
1. Click **+ Upload** button (top right)
2. Select these files from your computer:
   - `index_v2.html`
   - `founder_journey.jpg`
   - `sunset_portrait.jpg`
   - `cafe_work.jpg`
3. Wait for upload to complete (should take < 30 seconds)

### Step 5: Rename HTML File
1. Right-click `index_v2.html`
2. Click **Rename**
3. Change to: `index.html`
4. Click **Rename File**

### Step 6: Set as Default (Optional)
1. Click on `index.html`
2. Click **Set as Default** (top toolbar)
3. Click **Save**

### Step 7: Enable SSL
1. Go to **Security** section
2. Click **SSL/TLS**
3. Click **Manage SSL Sites**
4. Select `jamilbd.me` from dropdown
5. Click **Run AutoSSL**
6. Wait 5-10 minutes

### Step 8: Test Your Website
Visit: **https://jamilbd.me**

You should see your portfolio with all 3 photos! \ud83c\udf89

---

## \ud83d\udd0d Troubleshooting

### Issue: "404 Not Found"
- Make sure `index.html` is in `public_html` folder
- Check that all JPG files are uploaded
- Clear browser cache (Ctrl+F5)

### Issue: Images not showing
- Verify JPG filenames match exactly in HTML
- Check file permissions (should be 644)
- Ensure images are in same folder as HTML

### Issue: HTTP instead of HTTPS
- Complete Step 7 (Enable SSL)
- Wait 10 minutes for SSL to activate
- Force HTTPS in cPanel redirects

---

## \ud83d\udcf1 Mobile Test

After uploading, test on:
- Your phone (Chrome/Safari)
- Different screen sizes
- All sections should work

---

## \ud83d\udd27 Quick Customization

### Change Email
Open `index.html` in any text editor, find:
```html
<div class="contact-value">jamilhoseen@hotmail.com</div>
```
Replace with your preferred email.

### Change Phone
Find and update:
```html
<div class="contact-value">+880 1XXX-XXXXXX</div>
```

### Add More Photos
1. Upload your new JPG to `public_html`
2. Add to gallery section in HTML:
```html
<div class="gallery-item">
    <img src="your-photo.jpg" alt="Description">
</div>
```

---

## \ud83d\ude80 What's Next?

Once your portfolio is live, you can:
- [ ] Share on LinkedIn/Twitter
- [ ] Add to your email signature
- [ ] Create more pages (blog, services)
- [ ] Add contact form with backend
- [ ] Connect Google Analytics

---

## \ud83d\udcde Need Help?

If you get stuck at any step:
1. Take a screenshot
2. Tell me which step you're on
3. I'll help you fix it!

---

**Your portfolio will be live in 10 minutes!** \ud83d\ude80
