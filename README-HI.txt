ZK FASHION WEBSITE — STARTER PROJECT
===================================

इस ZIP में आपकी responsive men's fashion website का starter version है।

फाइलें:
- index.html       वेबसाइट का मुख्य पेज
- styles.css       Black + White + Gold डिजाइन
- products.js      Product नाम, category, कीमत, फोटो और WhatsApp नंबर
- script.js        Search, category filter, shopping bag और WhatsApp order flow

महत्वपूर्ण: अभी sample products और sample prices लगे हैं। ये असली stock या वास्तविक कीमतें नहीं हैं। Publish करने से पहले इन्हें बदलें।

WhatsApp नंबर सेट करना:
1. products.js खोलें।
2. window.ZK_WHATSAPP_NUMBER में 91XXXXXXXXXX को अपने WhatsApp Business नंबर से बदलें।
   उदाहरण: 919876543210 (केवल उदाहरण)
3. नंबर में +, space या dash न लगाएं।

Products बदलना:
products.js में window.ZK_PRODUCTS की सूची edit करें।
हर product में id, name, category, price, tag और image रखें।
Category इनमें से रखें: T-Shirts, Shirts, Jeans, Track Pants.
Image field में अपनी product photo का public image URL डालें।

मोबाइल से फाइलें edit करना:
- Acode या किसी HTML editor app में project folder खोल सकते हैं।
- बेहतर और सुरक्षित editing के लिए कंप्यूटर उपयोग करें।
- HTML/CSS/JS files को एक ही folder में रखें।

Free hosting:
- GitHub Pages या Netlify जैसी static hosting पर इसे deploy किया जा सकता है।
- Domain का free subdomain मिल सकता है; अपना .com domain आमतौर पर paid होता है।
- Hosting account बनाकर project files upload करनी होंगी।

सीमाएं और Admin Control:
- यह अभी frontend/static website है।
- Shopping bag browser में demo cart है; इसमें server पर order save नहीं होता।
- WhatsApp order बटन आपके नंबर पर message तैयार करता है।
- कोई secure admin login, central inventory database, order dashboard, payment gateway या automatic checkout शामिल नहीं है।
- Products बदलने के लिए products.js edit करके फिर site deploy/update करनी होगी।
- असली secure Admin Panel और multi-device order management के लिए backend/database/authentication की जरूरत होगी। केवल static HTML में password छिपाना सुरक्षित नहीं है।

Launch से पहले checklist:
[ ] Sample product names/prices हटाकर असली जानकारी डालें
[ ] अपनी product photos लगाएं
[ ] WhatsApp नंबर सेट और test करें
[ ] Size chart, shipping, return/refund और privacy जानकारी जोड़ें
[ ] मोबाइल पर पूरा checkout flow test करें
[ ] वास्तविक भुगतान लेने से पहले payment provider का account और policies सेट करें
