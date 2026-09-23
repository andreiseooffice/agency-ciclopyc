# CICLOPYC: Neon Core

Construiește o pagină de aterizare (landing page) de lux, în stil 3D dark-futuristic pentru agenția de web design CICLOPYC, folosind React, Tailwind CSS, Lucide Icons și Framer Motion.

Design & Temă:
- Fundal: Negru intens / pur (#0B0B0C și #000000), fundal cu grilă în perspectivă (perspective grid), efecte subtile de red glow (#FF2A3B / #E50914) și sticlă mată (dark glassmorphism).
- Culori & Accente: Tipografie albă curată, contrast ridicat, borduri luminoase neon roșu/crimson, colțuri rotunjite (rounded-2xl, rounded-3xl).

Structura și Secțiunile Paginii:
1. Floating Pill Navbar:
   - Fixed top-6, centrat (left-1/2 -translate-x-1/2 z-50), fundal frosted glass cu bordură fină.
   - Logo: CICLOPYC cu accent roșu.
   - Linkuri de navigare fluide: Acasă, Portofoliu, Statistici, Recenzii, Modele Site-uri (Shop), FAQ, Contact.
   - Buton CTA: "EXPLORE" cu iconiță și accent roșu strălucitor.

2. Hero Section:
   - Stânga:
     * Badge "WELCOME" cu punct luminos roșu pulsant.
     * Titlu gigant: "CICLOPYC" cu text gradient și reflexii.
     * Headline: "Site-uri web de înaltă performanță care transformă vizitatorii în clienți".
     * Sub-headline: "Fără șabloane obosite. Design futurist, viteză de încărcare sub 1s și optimizare pentru conversii".
     * Butoane CTA: "Programează o discuție" (stil roșu aprins cu glow) și "Vezi Proiectele" (stil dark glassmorphism).
     * Carduri Bento mici în partea de jos: "1.7K+ Clienți", "3K Lucrări".
   - Dreapta: Container dedicat cu element 3D / canvas futurist plutitor interactiv (folosind Three.js sau un canvas interactiv 3D geometric futurist cu aură roșie reactivă la mouse).

3. Portofoliu / Showcase:
   - Titlu: "Proiecte Selectate".
   - Grilă cu 3 carduri de mockups premium interactive (categorii precum E-commerce, Fintech, SaaS), efecte hover elegante "Vezi Proiect" și previzualizare/modal detaliu.

4. Statistici, Clienți & Recenzii:
   - Contoare animate cu metrici cheie: 99% Satisfacție, 100+ Site-uri Livrate, Încărcare <1s.
   - Bandă animată continuă cu logo-uri de companii (marquee animation).
   - Carduri de testimoniale/recenzii cu badge de 5 stele și detalii clienți.

5. Magazin Modele de Bază (Base Templates / Shop):
   - Grilă de modele pre-construite (ex: Salon & Beauty, Cafenea & Bistro, Imobiliare Premium).
   - Include listă de funcționalități, preț clar și buton interactiv "Trimite Comandă" cu deschidere modal sau selector.

6. Formular Audit Gratuit & CTA:
   - Box CTA cu impact vizual masiv, bordură roșie luminată cu efect de neon: "Solicită un Audit Web Gratuit".
   - Formular complet funcțional și interactiv: Nume, Email, URL Site Actual, Buget estimat și buton "Cere Audit" (cu feedback instant / toast la trimitere).

7. Secțiunea FAQ (Întrebări Frecvente):
   - Acordeon animat și fluid cu întrebări despre timpii de livrare, tehnologiile utilizate (React, Next/TanStack, Tailwind), mentenanță și opțiuni custom.

8. Subsol (Footer):
   - Minimalist, logo CICLOPYC, linkuri utile, iconițe rețele sociale (Twitter/X, GitHub, LinkedIn, Instagram) și informații fiscale/copyright.

Micro-interacțiuni & Rafinament:
- Animații Framer Motion (whileTap={{ scale: 0.95 }}, hover glow, intrare la scroll).
- Sistem de notificări (toast) la trimiterea formularelor.
- Design complet responsive (mobil, tabletă, desktop).

This project was built with [Lovable](https://lovable.dev).

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/a0b61bf1-718f-4f50-a8e1-a8e552e81a89).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
