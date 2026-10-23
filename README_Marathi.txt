AdhiraVerse Bharat History Atlas — GitHub Pages deployment package

या फोल्डरमधील index.html ही वेबसाइटची मुख्य फाइल आहे.

GitHub Pages वर प्रकाशित करण्याची पद्धत:
1. https://github.com येथे साइन इन करा.
2. New repository तयार करा. उदाहरणार्थ: adhira-verse-history-atlas
3. Repository Public ठेवा (GitHub Free वर सोपा मार्ग).
4. Add file > Upload files निवडा आणि या फोल्डरमधील index.html अपलोड करा.
5. Commit changes करा.
6. Repository > Settings > Pages उघडा.
7. Build and deployment मध्ये Deploy from a branch निवडा.
8. Branch: main आणि folder: /(root) निवडून Save करा.
9. GitHub Pages URL तयार होईपर्यंत थांबा. साधारणपणे https://USERNAME.github.io/REPOSITORY/ अशा स्वरूपाचा असेल.
10. URL स्वतः उघडून नकाशा नीट चालतो का तपासा.

Blogger मध्ये Embed:
Blogger > Pages > New Page > HTML view मध्ये खालील कोड टाका.
iframe मधील src मध्ये GitHub Pages वरून मिळालेला खरा URL वापरा.

<div style="width:100%;max-width:1200px;margin:auto;">
  <iframe src="https://USERNAME.github.io/REPOSITORY/" title="AdhiraVerse Bharat History Atlas" loading="lazy" style="width:100%;height:850px;border:0;border-radius:8px;" allowfullscreen></iframe>
</div>

महत्त्वाचे:
- USERNAME आणि REPOSITORY हे प्रत्यक्ष GitHub माहितीने बदला.
- हा पॅकेज अपलोड करण्यासाठी तयार आहे; पण साइट स्वतःहून प्रकाशित झालेली नाही.
- प्रकाशित केल्यानंतर desktop आणि mobile दोन्हीवर तपासा.
