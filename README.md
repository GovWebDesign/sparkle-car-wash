# SPARKLE CAR WASH – Accra, Ghana

**24/7 Premium Car Wash Booking System**  
*Instant WhatsApp bookings | Mobile Money payments | Google Sheets management | Service Selection*

 **Live Demo**: [https://govwebdesign.github.io/sparkle-car-wash](https://govwebdesign.github.io/sparkle-car-wash)  
 [**Book Now**](https://govwebdesign.github.io/sparkle-car-wash?utm_source=github&utm_medium=readme&utm_campaign=docs_booking)  
📞 **Support (Ghana):** [+233 50 877 2690](https://wa.me/233508772690)

![Homepage Preview](/images/exterior-wash.jpg)

> 🌐 This project is optimized for **Ghana**, but can be adapted for other countries by changing phone numbers, currency, and labels.

---

## Key Features

| Feature                 | Benefit                                                                  |
|-------------------------|--------------------------------------------------------------------------|
| **1-Click WhatsApp**    | Customers message you directly — no app install needed                  |
| **Mobile Money Ready**  | Accept MTN, Vodafone & AirtelTigo instantly                             |
| **Auto Sheets Logging** | Bookings log automatically into Google Sheets with selected services    |
| **24/7 Online Access**  | Runs anytime, even on holidays                                           |
| **Service Selection**   | Users choose from predefined services (e.g., Exterior Wash, Combo)      |
| **Thank-You Confirmation** | Redirects users to a thank-you page with auto-redirect and analytics tracking |

---

## 🛠️ Technical Stack

### Frontend (Customer Interface)

- **Tech:** HTML5, CSS3, JavaScript  
- **Performance:** Loads in under 1s on MTN 4G (verified via Google PageSpeed Insights).
- **Local Testing Note:** To test locally with Live Server, update the Google Apps Script to include `Access-Control-Allow-Origin: http://127.0.0.1:5500` in the response headers. Switch to `https://govwebdesign.github.io` after deployment.

### Backend (Booking Management)

- **Powered by:** Google Apps Script with Google Sheets as a lightweight DB.

### 📊 Analytics

- **Tracking:** Google Analytics 4 (GA4) with tracking ID `G-E7CVDKBNL5` (replace for your project). Tracks page views and events like form submissions.

---

## ⚙️ Setup Guide

### For Business Owners

- **Bookings:** Customers select a service and contact you via WhatsApp or the contact form.
- **Payments:** Receive mobile money notifications.
- **Management:** View all bookings, including selected services, in a live Google Sheet.

### For Developers

```bash
# Clone this repository
git clone https://github.com/GovWebDesign/sparkle-car-wash.git

# Navigate into the project
cd sparkle-car-wash
```

To deploy:

1. Go to **GitHub Settings > Pages**.  
2. Set the source to the **main branch**, folder `/` (root).  
3. Save and wait for your live site.

---

## 🌍 Customization Tips

| Element            | How to Customize                                          |
|--------------------|-----------------------------------------------------------|
| **WhatsApp Number**| Replace `233508772690` with your country code and phone   |
| **Currency**       | Change pricing text from GHS to your local currency       |
| **Language**       | Translate all button labels, messages, and service options|
| **Payment System** | Swap MoMo with Paystack, Stripe, or other methods         |
| **Google Sheet**   | Use your own spreadsheet link and Google Apps Script URL |
| **Google Analytics** | Replace `G-E7CVDKBNL5` in HTML files with your tracking ID |
| **Services**       | Update the `<select>` options in `index.html` with your services |

---

## Contact & Location (Ghana Sample)

- **Location:** Near East Legon Shell Station, Accra, Ghana  
- **Hours:** Open 24/7, all year round  
- **Mobile Money:** MTN | Vodafone | AirtelTigo  

---

## 💳 Accepted Payments

![MTN Mobile Money](https://img.shields.io/badge/MTN_MoMo-FFC600?logo=mtn&logoColor=black)  
![Vodafone Cash](https://img.shields.io/badge/Vodafone_Cash-E60000?logo=vodafone&logoColor=white)  
![AirtelTigo Money](https://img.shields.io/badge/AirtelTigo-FF0000?logo=airtel&logoColor=white)  

---

## 📲 Scan to Book Instantly

[![WhatsApp QR Code](https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=https://wa.me/233508772690?text=Hello%20SPARKLE%20CAR%20WASH%2C%20I%20want%20to%20book%20a%20wash)](https://wa.me/233508772690)  
*Scan with your mobile money app*

---

## 📜 License

Licensed under the MIT License — see [LICENSE.txt](./LICENSE.txt) for details.
