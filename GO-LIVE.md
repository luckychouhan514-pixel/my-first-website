# Shivalaya Paper Workks – Website live karne ki guide

## 1. Domain kharidna (~Rs 500-1,500 / year)
- Cloudflare Registrar, Hostinger, GoDaddy ya BigRock se domain lo (jaise shivalayapaperworkks.in).
- Domain **apne naam / apne email** se kharido taaki ownership aapke paas rahe.
- Renewal price zaroor dekho (pehle saal ka offer sasta hota hai).

## 2. Free hosting par upload (Netlify - sabse aasan)
1. netlify.com par free account banao.
2. "Add new site" > "Deploy manually".
3. Poora `shivalaya-paper-works-site` folder drag & drop karo.
4. Site turant ek free link par live ho jayegi. Mobile par test karo.

(Alternative: Cloudflare Pages ya GitHub Pages. Commercial use ke liye unki terms ek baar check kar lo.
Agar paid shared hosting lena ho to cPanel ke public_html mein sab files upload kar do.)

## 3. Domain jodna
1. Netlify > Domain management > "Add custom domain".
2. Registrar mein diye gaye DNS records (ya nameservers) daal do.
3. 5 minute se 24 ghante mein domain chalne lagta hai. HTTPS (SSL) free apne aap lag jata hai.

## 4. Live hone ke baad check karo
- Contact form aur "Send enquiry" popup: WhatsApp khulna chahiye (number +91 62663 05133).
- WhatsApp icon, products page, zoom (client images), map, phone/email links.
- Mobile aur desktop dono par.

## 5. Email backup (optional, free)
1. web3forms.com par apna email daal ke free access key lo.
2. `assets/js/site.js` mein `EMAIL_BACKUP_KEY = ''` ke andar key paste karo.
3. Ab har enquiry aapke email par bhi aayegi (customer WhatsApp par Send na bhi kare to).

## Zaroori baat
Enquiry WhatsApp par tab aati hai jab customer WhatsApp mein **Send** dabata hai. Isiliye email backup (step 5) rakhna accha hai.
