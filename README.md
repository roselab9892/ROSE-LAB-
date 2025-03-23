# Creating a README file that explains the project details
readme_content = """
# Rose Lab Diagnostics Health Care Centre Website

This is the official website for **Rose Lab Diagnostics Health Care Centre**, a pathology lab located in Naigaon (East), Maharashtra.

## 🌐 Website Features

- ✅ Fully responsive design
- 🧪 List of all major pathology tests offered
- 📝 Online test booking form with WhatsApp integration
- 📍 Google Maps location embedding
- 📞 Contact information (phone, WhatsApp, and email)
- 💬 WhatsApp chat shortcut
- 📄 Extended description about the lab and services

## 📍 Location

**Address:**  
Shop No. 2, Vitthal Apartment, Opp. Vitthal Mandir, Wakipada Rickshaw Stand,  
Naigaon (East), Tal. Vasai, Dist. Palghar, Maharashtra 401208

## 📞 Contact Information

- **Booking Phone:** 9898389027  
- **WhatsApp:** 7977824758  
- **Email:** roselab821988@gmail.com

## 🚀 How to Launch the Website

1. Download the `rose_lab_website.html` file.
2. Open it in your browser to view the website locally.
3. To make it live, upload it to a free service like:
   - [Netlify](https://www.netlify.com/)
   - [GitHub Pages](https://pages.github.com/)
   - [Vercel](https://vercel.com/)

---

Made with ❤️ for Rose Lab Diagnostics Health Care Centre.
"""

# Save the README file
readme_path = "/mnt/data/README.txt"
with open(readme_path, "w", encoding="utf-8") as f:
    f.write(readme_content)

readme_path
